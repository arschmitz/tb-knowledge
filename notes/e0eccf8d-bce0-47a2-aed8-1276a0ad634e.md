<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:07:00.193Z","paths":["toolkit/components/extensions/Schemas.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"toolkit","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox toolkit/components/extensions/Schemas.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## localize at 449 to 451

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:449-451`; body SHA-256 `a4d315cd9145ea4bc4b6d862cf72fedb6e79a2b30aa8f6e7ac44f1d2585002eb`; rule `return-bound-parameter`.

Returns the bound parameter value without calling it or reading one of its properties. This is the body return value. The caller can supply any value; constructor invocation can ignore it.

## hasPermission at 529 to 531

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:529-531`; body SHA-256 `b633a7017e1e4c121bf0545432b9933773b8b91c02784c7b601ee0fc60fcecc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns false. This is the body return value; constructor invocation can ignore it.

## isPermissionRevokable at 542 to 544

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:542-544`; body SHA-256 `b633a7017e1e4c121bf0545432b9933773b8b91c02784c7b601ee0fc60fcecc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns false. This is the body return value; constructor invocation can ignore it.

## checkBaseType at 1654 to 1656

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:1654-1656`; body SHA-256 `b633a7017e1e4c121bf0545432b9933773b8b91c02784c7b601ee0fc60fcecc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns false. This is the body return value; constructor invocation can ignore it.

## checkBaseType at 1689 to 1691

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:1689-1691`; body SHA-256 `80c08e6eeb8ca6c560afeedad34d1836f6d34b7df89794491c603a6b0b3e50e5`; rule `return-primitive`.

After parameter binding succeeds, the local body returns true. This is the body return value; constructor invocation can ignore it.

## anonymous@3087:21 at 3087 to 3087

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:3087-3087`; body SHA-256 `44136fa355b3678a1146ad16f7e8649e94fb4fc21fe77e8310c060f61caaff8a`; rule `empty-or-bare-return`.

After parameter binding succeeds, the local body completes with undefined. This is the body return value; constructor invocation can ignore it.

## anonymous@4019:14 at 4019 to 4021

Evidence: `toolkit/components/extensions/Schemas.sys.mjs:4019-4021`; body SHA-256 `456c39a3a1d86d4230736d78c064ceda910de630b5ebcdb9c438dcbef4e1fa23`; rule `return-bound-parameter`.

Returns the bound parameter results without calling it or reading one of its properties. This is the body return value. The caller can supply any value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
