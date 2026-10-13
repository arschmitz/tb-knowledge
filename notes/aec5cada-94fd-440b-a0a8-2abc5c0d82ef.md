<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":[".babel-eslint.rc.js",".prettierrc.js",".stylelintrc.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/(root) JavaScript function map 1

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### .babel-eslint.rc.js

Blob: `ebaf8fec3a7609da8bbe882eef52193e81cb865f`. Role: source. Parse: module.


### .prettierrc.js

Blob: `1abf65c5eb50bfb268d90e0923f26473b8114eac`. Role: source. Parse: module.


### .stylelintrc.js

Blob: `19c7310d7471d55c52dca24ca8095f798fb44d60`. Role: source. Parse: module.

- readFile @13-18; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
