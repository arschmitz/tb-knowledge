<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:06:59.497Z","paths":["services/fxaccounts/FxAccountsPairingChannel.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"services","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox services/fxaccounts/FxAccountsPairingChannel.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## noop at 234 to 234

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:234-234`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## initialize at 1469 to 1471

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:1469-1471`; body SHA-256 `c4c2137e36a8e4907871332c3d4dfe4f3a069a3b5938967a792930346512d0ff`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. The async function promise fulfills with undefined after this body completes.

## NONE at 2733 to 2735

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:2733-2735`; body SHA-256 `ff5177fb1e0146f19eb97a6c01749948751c44ef459ea030a217ff470506e14f`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 0. This is the body return value; constructor invocation can ignore it.

## CAPTURING_PHASE at 2741 to 2743

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:2741-2743`; body SHA-256 `e83aa5f3b4d4212f9103546aa68a5cf6d91fdd3ff4b2373087ece91935274385`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 1. This is the body return value; constructor invocation can ignore it.

## AT_TARGET at 2749 to 2751

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:2749-2751`; body SHA-256 `11a2c152e4b23008e6b0efe1febbffc49d175e2d269d5dd85827677a9d0a9f61`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 2. This is the body return value; constructor invocation can ignore it.

## BUBBLING_PHASE at 2757 to 2759

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:2757-2759`; body SHA-256 `a2aceeed7850bed3c363d8257ed1d33450a07f305934c98fd42ee87df76ed773`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 3. This is the body return value; constructor invocation can ignore it.

## initEvent at 2894 to 2896

Evidence: `services/fxaccounts/FxAccountsPairingChannel.sys.mjs:2894-2896`; body SHA-256 `864a18c5447b7acbd1d6c9ddbabb0bd0d3df0463d141c17952f27975eea59dd1`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
