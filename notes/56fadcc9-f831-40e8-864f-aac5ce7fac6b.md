<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:00.383Z","paths":["toolkit/content/widgets/findbar.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"unresolved","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/content/widgets/findbar.js direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## connectedMoveCallback at 300 to 303

Evidence: `toolkit/content/widgets/findbar.js:300-303`; body SHA-256 `addcfbccf68cc7e0bc41c489d8388b712d8b78e4a4b5a09b845eb29bde017bc6`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## onHighlightFinished at 1343 to 1345

Evidence: `toolkit/content/widgets/findbar.js:1343-1345`; body SHA-256 `3c8556880c96b4e5c9422f331baebefddf66a1f87cd86e35766ca043256759d0`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
