<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:00.202Z","paths":["toolkit/components/downloads/Downloads.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/components/downloads/Downloads.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## PUBLIC at 38 to 40

Evidence: `toolkit/components/downloads/Downloads.sys.mjs:38-40`; body SHA-256 `f6fed366ef64b137328d4d83b2d845e3acb0a6af647cb03700e9f276aef25e3f`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "{Downloads.PUBLIC}". This is the body return value; constructor invocation can ignore it.

## PRIVATE at 44 to 46

Evidence: `toolkit/components/downloads/Downloads.sys.mjs:44-46`; body SHA-256 `4ec436f19bb80148cb91e975c0cfb0648bd670174dedfba27773b16fd83c6dd1`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "{Downloads.PRIVATE}". This is the body return value; constructor invocation can ignore it.

## ALL at 50 to 52

Evidence: `toolkit/components/downloads/Downloads.sys.mjs:50-52`; body SHA-256 `ac2fdb677386b58c9a119d6cdee085bc3581d4aa6d31a61ecac7583790d6e948`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "{Downloads.ALL}". This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
