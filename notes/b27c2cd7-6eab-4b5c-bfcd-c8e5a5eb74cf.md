<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:02.599Z","paths":["devtools/shared/performance-new/profiler_get_symbols.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"devtools","runtime":"unresolved","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox devtools/shared/performance-new/profiler_get_symbols.js direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## register at 139 to 139

Evidence: `devtools/shared/performance-new/profiler_get_symbols.js:139-139`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## unregister at 139 to 139

Evidence: `devtools/shared/performance-new/profiler_get_symbols.js:139-139`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## __wbg_init_memory at 496 to 498

Evidence: `devtools/shared/performance-new/profiler_get_symbols.js:496-498`; body SHA-256 `f8a5a26e3056eb6fb06deeb3dbccfd88ae74900200c98c70b5966bbb7ec9d4de`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

Observed local lexical call sites: `devtools/shared/performance-new/profiler_get_symbols.js:515-515` (ExpressionStatement); `devtools/shared/performance-new/profiler_get_symbols.js:538-538` (ExpressionStatement). Reaching these calls at runtime is unverified.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
