<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:02.144Z","paths":["toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## _generateFooterLabel at 122 to 124

Evidence: `toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs:122-124`; body SHA-256 `0f2adcb3818c391843fed79939750332cb2bbd2b7806a2865c21d625c72db16d`; rule `return-primitive`.

After parameter binding succeeds, the local body returns null. This is the body return value; constructor invocation can ignore it.

## _getSecondaryLabel at 178 to 180

Evidence: `toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs:178-180`; body SHA-256 `f28868e16d8ba7322f80e4bcce49cad1577b68ac333cd0efa2143b8eb4d3906f`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "". This is the body return value; constructor invocation can ignore it.

## _generateLabels at 182 to 182

Evidence: `toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs:182-182`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## isRemovableAt at 301 to 303

Evidence: `toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs:301-303`; body SHA-256 `b633a7017e1e4c121bf0545432b9933773b8b91c02784c7b601ee0fc60fcecc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns false. This is the body return value; constructor invocation can ignore it.

## removeValueAt at 310 to 312

Evidence: `toolkit/components/formautofill/ProfileAutoCompleteResult.sys.mjs:310-312`; body SHA-256 `8aeea010e66b07b2f7d8012f02cf78402e10680132cec64e4bea8d80799c78db`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
