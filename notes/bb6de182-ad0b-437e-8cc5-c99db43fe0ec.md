<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:00.237Z","paths":["browser/components/search/SearchOneOffs.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"browser","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox browser/components/search/SearchOneOffs.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## buttonWidth at 206 to 208

Evidence: `browser/components/search/SearchOneOffs.sys.mjs:206-208`; body SHA-256 `5c81fe266a26fd25d7ce3d92ea548aefe06a81f9ab8d5c0b81cf7782d03931bc`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 48. This is the body return value; constructor invocation can ignore it.

## _maxInlineAddEngines at 411 to 413

Evidence: `browser/components/search/SearchOneOffs.sys.mjs:411-413`; body SHA-256 `473decc44eb0ae50cc6b1f8d4435b162273b45993bb2a802981d6e16242aaf3c`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 3. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
