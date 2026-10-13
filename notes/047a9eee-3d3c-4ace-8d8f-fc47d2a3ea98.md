<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T15:06:51.724Z","paths":["chat/protocols/matrix/lib/matrix-events-sdk/events/EmoteEvent.js"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source,configured-imported-path-match","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"chat","runtime":"unresolved","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":true,"generated":false}} -->
# thunderbird chat/protocols/matrix/lib/matrix-events-sdk/events/EmoteEvent.js direct local body contracts

These are deterministic explanations of complete simple local bodies at `87d0159c7149a43253964c2cb6917939557dc799`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## anonymous@38:267 at 38 to 38

Evidence: `chat/protocols/matrix/lib/matrix-events-sdk/events/EmoteEvent.js:38-38`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## get at 61 to 63

Evidence: `chat/protocols/matrix/lib/matrix-events-sdk/events/EmoteEvent.js:61-63`; body SHA-256 `6706609a43ce24f9219b6e53b2ee29a10daa0d9df002bea7d676303a0b874a0e`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
