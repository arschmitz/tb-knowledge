<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:00.162Z","paths":["toolkit/components/extensions/ExtensionParent.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/components/extensions/ExtensionParent.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## isProxyContextParent at 623 to 625

Evidence: `toolkit/components/extensions/ExtensionParent.sys.mjs:623-625`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## logActivity at 755 to 758

Evidence: `toolkit/components/extensions/ExtensionParent.sys.mjs:755-758`; body SHA-256 `116b9455aaa2cd63bdc4eb145df485a70c1ab8818f533812e2417dba69af0655`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## anonymous@2530:13 at 2530 to 2533

Evidence: `toolkit/components/extensions/ExtensionParent.sys.mjs:2530-2533`; body SHA-256 `b9fc3961eafe5cdebd0f4894788bf54469a3d0f23253c5948b1b0657b5872a0c`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## anonymous@2588:9 at 2588 to 2588

Evidence: `toolkit/components/extensions/ExtensionParent.sys.mjs:2588-2588`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## anonymous@2592:10 at 2592 to 2592

Evidence: `toolkit/components/extensions/ExtensionParent.sys.mjs:2592-2592`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
