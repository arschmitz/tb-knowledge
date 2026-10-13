<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:02.387Z","paths":["toolkit/components/formautofill/FormAutofillSync.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/components/formautofill/FormAutofillSync.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## _reconcile at 292 to 294

Evidence: `toolkit/components/formautofill/FormAutofillSync.sys.mjs:292-294`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. The async function promise fulfills with this primitive value after the return.

## prefName at 366 to 368

Evidence: `toolkit/components/formautofill/FormAutofillSync.sys.mjs:366-368`; body SHA-256 `3022b241ec03a379e2137880ab80ff314fad89978892dacabc529ce9ff2ec394`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "addresses". This is the body return value; constructor invocation can ignore it.

## prefName at 397 to 399

Evidence: `toolkit/components/formautofill/FormAutofillSync.sys.mjs:397-399`; body SHA-256 `3022b241ec03a379e2137880ab80ff314fad89978892dacabc529ce9ff2ec394`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "addresses". This is the body return value; constructor invocation can ignore it.

## prefName at 480 to 482

Evidence: `toolkit/components/formautofill/FormAutofillSync.sys.mjs:480-482`; body SHA-256 `b98f3eb2770e8390cdf6a516dd15d38ec92238edb75db43592aca5d1c9d939a0`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "creditcards". This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
