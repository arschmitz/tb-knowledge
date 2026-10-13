<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T08:21:33.801338+00:00", "paths": ["netwerk/dns/nsEffectiveTLDService.cpp", "netwerk/dns/nsEffectiveTLDService.h", "netwerk/dns/nsIEffectiveTLDService.idl", "netwerk/build/components.conf", "netwerk/dns/tests/unit/test_nsEffectiveTLDService_getSite.js", "netwerk/dns/tests/unit/xpcshell.toml", "netwerk/test/unit/test_psl.js", "netwerk/test/unit/test_bug414122.js"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "detection-body-study-20261013", "verification": "Scoped body/caller/assertion reading; native run has older-build limits"}} -->
# Gecko effective-site service defines Calendar password scope and Account Hub host grouping

Every local body in effective-site CPP469 lines, header80 and full interface read.
components.conf:145–155 maps Services.eTLD to the static singleton constructor.
Header:20–77 uses fixed AddRef/Release return values rather than deleting singleton,
holds a non-owning graph span over compiled static data and a main-thread-only
recent-result cache. The cache is created before final shutdown and ClearOnShutdown
owns its release. Native lookup state is shared service state, not per calendar.

GetSite:126–153 obtains URI scheme, calls GetSchemelessSite, rejects invalid dot/
hostless non-file case and builds scheme://site. GetSchemelessSite:95–105 requests
base domain and falls back to serialized host/IPv6 brackets for IP or insufficient
domain levels. Port, credentials and path are not part of returned site. FromHost:
110–120 handles bare host similarly. BaseDomain entry:76–87 extracts innermost URI
host; FromHost:187–201 normalizes ASCII/IDN via native helper then calls same lookup.
Those external URI/IDN implementations remain separate source targets.

GetBaseDomainInternal:221–401 strips/retains trailing dot, rejects malformed empty
labels and IP, and walks domain labels using actual Dafsa graph tags. Wildcard
and exception tags choose the effective suffix; unknown suffix uses final label
unless known-only requested. It counts requested extra parts and fails if too
few. Ordinary base-domain lookups cache both success and failure on main thread;
cached failures are checked before using cached text. Other threads bypass cache.
Known-suffix methods and HasKnownPublicSuffix:412–469 use graph lookup; the latter
searches up to its explicit loop limit. HasRootDomain delegates to native DNS helper;
complete helper behavior is outside this file review.

Thunderbird exact callers: calProviderDetectionUtils:66–96 calls getSite and
allows HTTPS upgrade for an HTTP site, not downgrade. DetectionSession.promptAuth
checks that result before exposing password. Account Hub email.mjs:1904–1913 uses
getSchemelessSiteFromHost to choose incoming host fallback. Site equality here
differs from CalDavSession's exact prePath OAuth origin contract.

Direct test_nsEffectiveTLDService_getSite.js:10–106 checks invalid dot, aliases,
trailing dot, IPv4/IPv6, removed port/path/credentials, subdomains, co.uk and
internationalized labels across site/schemeless/FromHost APIs. It ran PASS in
installed Thunderbird159.0a1 build20261006201633 on darwin/arm64 at
2026-10-13T08:06:14.190Z–08:06:15.077Z. Native source stamp is unknown; this is
not exact-current-CPP verification. PSL tests separately compare domain/suffix
values, not Calendar credential decisions; their data inputs were not manually
reviewed in full and they were not run here.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Paths and line ranges or named task anchors
refer to these exact commits. Read with `git show REVISION:repository-relative-path`.
Direct source relationships, inferred effects and unresolved dispatch are separated.
Static test assertions do not establish a pass. Product run results identify the
observed build and its unknown native revision. Private logs, indexes and local
paths stay outside shared knowledge. Suite and deliberate instructions are unchanged.
