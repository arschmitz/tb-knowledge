<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:02.512Z","paths":["toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## type at 182 to 184

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:182-184`; body SHA-256 `92506b1e0ae32409b67434165e78d6440d390afc6bc760e93b9de318f1b20af6`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "plugin". This is the body return value; constructor invocation can ignore it.

## isGMPlugin at 185 to 187

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:185-187`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## creator at 191 to 193

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:191-193`; body SHA-256 `0f2adcb3818c391843fed79939750332cb2bbd2b7806a2865c21d625c72db16d`; rule `return-primitive`.

After parameter binding succeeds, the local body returns null. This is the body return value; constructor invocation can ignore it.

## fullDescription at 201 to 203

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:201-203`; body SHA-256 `0f2adcb3818c391843fed79939750332cb2bbd2b7806a2865c21d625c72db16d`; rule `return-primitive`.

After parameter binding succeeds, the local body returns null. This is the body return value; constructor invocation can ignore it.

## size at 288 to 290

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:288-290`; body SHA-256 `304b4c9218216316607ed2b8a17f08cf9678b8decae19170e9d49efebb2cc621`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 0. This is the body return value; constructor invocation can ignore it.

## isCompatible at 323 to 325

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:323-325`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## isPlatformCompatible at 327 to 329

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:327-329`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## providesUpdatesSecurely at 331 to 333

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:331-333`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## foreignInstall at 335 to 337

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:335-337`; body SHA-256 `b633a7017e1e4c121bf0545432b9933773b8b91c02784c7b601ee0fc60fcecc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns false. This is the body return value; constructor invocation can ignore it.

## isCompatibleWith at 343 to 345

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:343-345`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## anonymous@570:56 at 570 to 570

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:570-570`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## name at 732 to 734

Evidence: `toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs:732-734`; body SHA-256 `d436d12597ebba0f83bead0ce48cda80e770b033f916e613c899e6e16b805d1e`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "GMPProvider". This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
