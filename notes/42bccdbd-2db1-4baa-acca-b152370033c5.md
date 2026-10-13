<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:17:22.071Z","paths":["docs/jsdoc.conf.js"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-study-20261013"}} -->
# thunderbird/docs JavaScript function map 16

Revision: `87d0159c7149a43253964c2cb6917939557dc799`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### docs/jsdoc.conf.js

Blob: `c1d702325f12a26463e909141a55cf90308de43f`. Role: source. Parse: module.

- readFile @10-16; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
