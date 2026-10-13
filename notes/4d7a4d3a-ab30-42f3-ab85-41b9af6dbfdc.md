<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/react/react.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/react/react.min.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/todomvc-common/base.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/app.jsx","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/footer.jsx","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/todoItem.jsx","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/utils.jsx","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.app.930ad8b83126862d7445.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.manifest.e81199b00da2921d9c94.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.vendor.577c6bc09319b27fed34.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/app.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/bootstrap.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/controller.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/controller.test.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/helpers.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/memory.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/model.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/store.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/template.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/todo.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/view.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/webpack.config.babel.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/node_modules/todomvc-common/base.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/app.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/controller.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/helpers.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/model.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/store.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/template.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/view.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/app.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/controller.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/helpers.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/model.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/store.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/template.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/view.js","third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/node_modules/todomvc-common/base.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/third_party JavaScript function map 1270

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/react/react.js

Blob: `c58ec133f0ea3816a31162d81973c82c3177f684`. Role: imported-path,source. Parse: module.

- (anonymous) @4-11327; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-4; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-53; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @5-5; FunctionExpression; parameters=3; async=false; generator=false
- i @5-5; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @5-5; FunctionExpression; parameters=1; async=false; generator=false
- $ @40-49; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @53-144; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @144-243; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @173-175; FunctionExpression; parameters=1; async=false; generator=false
- createMarkupForStyles @193-206; FunctionExpression; parameters=1; async=false; generator=false
- setValueForStyles @215-237; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @243-336; FunctionExpression; parameters=3; async=false; generator=false
- putListener @285-289; FunctionExpression; parameters=3; async=false; generator=false
- getListener @296-299; FunctionExpression; parameters=2; async=false; generator=false
- deleteListener @307-312; FunctionExpression; parameters=2; async=false; generator=false
- deleteAllListeners @319-323; FunctionExpression; parameters=1; async=false; generator=false
- __purge @328-330; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @336-733; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @337-732; FunctionExpression; parameters=0; async=false; generator=false
- shouldUseChangeEvent @389-394; FunctionDeclaration; parameters=1; async=false; generator=false
- manualDispatchChangeEvent @404-418; FunctionDeclaration; parameters=1; async=false; generator=false
- startWatchingForChangeEventIE8 @420-424; FunctionDeclaration; parameters=2; async=false; generator=false
- stopWatchingForChangeEventIE8 @426-433; FunctionDeclaration; parameters=0; async=false; generator=false
- getTargetIDForChangeEvent @435-442; FunctionDeclaration; parameters=3; async=false; generator=false
- handleEventsForChangeEventIE8 @443-455; FunctionDeclaration; parameters=3; async=false; generator=false
- shouldUseInputEvent @492-497; FunctionDeclaration; parameters=1; async=false; generator=false
- get @504-506; FunctionExpression; parameters=0; async=false; generator=false
- set @507-511; FunctionExpression; parameters=1; async=false; generator=false
- startWatchingForValueChange @519-530; FunctionDeclaration; parameters=2; async=false; generator=false
- stopWatchingForValueChange @536-549; FunctionDeclaration; parameters=0; async=false; generator=false
- handlePropertyChange @555-566; FunctionDeclaration; parameters=1; async=false; generator=false
- getTargetIDForInputEvent @571-580; FunctionDeclaration; parameters=3; async=false; generator=false
- handleEventsForInputEventIE @583-606; FunctionDeclaration; parameters=3; async=false; generator=false
- getTargetIDForInputEventIE @609-631; FunctionDeclaration; parameters=3; async=false; generator=false
- shouldUseClickEvent @637-645; FunctionDeclaration; parameters=1; async=false; generator=false
- getTargetIDForClickEvent @647-654; FunctionDeclaration; parameters=3; async=false; generator=false
- extractEvents @678-726; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @733-880; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @734-879; FunctionExpression; parameters=0; async=false; generator=false
- _getNodesByOriginalIndex @786-803; FunctionExpression; parameters=2; async=false; generator=false
- _removeChildrenByOriginalIndex @811-818; FunctionExpression; parameters=2; async=false; generator=false
- _placeNodesAtDestination @832-858; FunctionExpression; parameters=3; async=false; generator=false
- manageChildren @860-866; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @880-1115; FunctionExpression; parameters=3; async=false; generator=false
- injectDOMPropertyConfig @941-999; FunctionExpression; parameters=1; async=false; generator=false
- isCustomAttribute @1081-1087; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1083-1085; FunctionExpression; parameters=1; async=false; generator=false
- getDefaultValueForProperty @1097-1108; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1115-1235; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1142-1144; FunctionExpression; parameters=1; async=false; generator=false
- createMarkupForProperty @1158-1175; FunctionExpression; parameters=2; async=false; generator=false
- setValueForProperty @1184-1204; FunctionExpression; parameters=3; async=false; generator=false
- deleteValueForProperty @1212-1229; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1235-1467; FunctionExpression; parameters=3; async=false; generator=false
- validateMarkupParams @1281-1285; FunctionExpression; parameters=2; async=false; generator=false
- renderMarkup @1352-1368; FunctionDeclaration; parameters=1; async=false; generator=false
- insertNodeAfterNode @1379-1392; FunctionDeclaration; parameters=3; async=false; generator=false
- inefficientlyInsertHTMLCollectionAfter @1401-1417; FunctionDeclaration; parameters=3; async=false; generator=false
- dangerouslyInsertMarkupAt @1430-1437; FunctionDeclaration; parameters=3; async=false; generator=false
- dangerouslyReplaceNodeWithMarkup @1448-1458; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1467-1626; FunctionExpression; parameters=3; async=false; generator=false
- className @1618-1620; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1626-1669; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1669-1780; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1670-1779; FunctionExpression; parameters=0; async=false; generator=false
- extractEvents @1726-1773; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @1780-1849; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1849-1912; FunctionExpression; parameters=3; async=false; generator=false
- listen @1880-1886; FunctionExpression; parameters=3; async=false; generator=false
- capture @1894-1907; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1912-2104; FunctionExpression; parameters=3; async=false; generator=false
- executeDispatchesAndRelease @1955-1969; FunctionExpression; parameters=1; async=false; generator=false
- extractEvents @2040-2063; FunctionExpression; parameters=4; async=false; generator=false
- enqueueEvents @2072-2076; FunctionExpression; parameters=1; async=false; generator=false
- processEventQueue @2083-2094; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2104-2350; FunctionExpression; parameters=3; async=false; generator=false
- recomputePluginOrdering @2143-2177; FunctionDeclaration; parameters=0; async=false; generator=false
- publishEventForPlugin @2187-2202; FunctionDeclaration; parameters=2; async=false; generator=false
- publishRegistrationName @2212-2221; FunctionDeclaration; parameters=2; async=false; generator=false
- injectEventPluginOrder @2254-2262; FunctionExpression; parameters=1; async=false; generator=false
- injectEventPluginsByName @2274-2295; FunctionExpression; parameters=1; async=false; generator=false
- getPluginModuleForEvent @2304-2323; FunctionExpression; parameters=1; async=false; generator=false
- _resetEventPlugins @2329-2344; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2350-2537; FunctionExpression; parameters=3; async=false; generator=false
- isEndish @2377-2381; FunctionDeclaration; parameters=1; async=false; generator=false
- isMoveish @2383-2386; FunctionDeclaration; parameters=1; async=false; generator=false
- isStartish @2387-2390; FunctionDeclaration; parameters=1; async=false; generator=false
- validateEventDispatches @2394-2409; FunctionExpression; parameters=1; async=false; generator=false
- forEachEventDispatch @2417-2434; FunctionDeclaration; parameters=2; async=false; generator=false
- executeDispatch @2442-2444; FunctionDeclaration; parameters=3; async=false; generator=false
- executeDispatchesInOrder @2449-2453; FunctionDeclaration; parameters=2; async=false; generator=false
- executeDispatchesInOrderStopAtTrue @2462-2484; FunctionDeclaration; parameters=1; async=false; generator=false
- executeDirectDispatch @2495-2511; FunctionDeclaration; parameters=1; async=false; generator=false
- hasDispatches @2517-2519; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2537-2718; FunctionExpression; parameters=3; async=false; generator=false
- injectInstanceHandle @2576-2581; FunctionExpression; parameters=1; async=false; generator=false
- validate @2582-2589; FunctionExpression; parameters=0; async=false; generator=false
- listenerAtPhase @2596-2600; FunctionDeclaration; parameters=3; async=false; generator=false
- accumulateDirectionalDispatches @2608-2621; FunctionDeclaration; parameters=3; async=false; generator=false
- accumulateTwoPhaseDispatchesSingle @2630-2638; FunctionDeclaration; parameters=1; async=false; generator=false
- accumulateDispatches @2646-2655; FunctionDeclaration; parameters=3; async=false; generator=false
- accumulateDirectDispatchesSingle @2662-2666; FunctionDeclaration; parameters=1; async=false; generator=false
- accumulateTwoPhaseDispatches @2668-2673; FunctionDeclaration; parameters=1; async=false; generator=false
- accumulateEnterLeaveDispatches @2675-2686; FunctionDeclaration; parameters=4; async=false; generator=false
- accumulateDirectDispatches @2689-2694; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2718-2764; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2719-2763; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2764-2879; FunctionExpression; parameters=3; async=false; generator=false
- oneArgumentPooler @2792-2801; FunctionExpression; parameters=1; async=false; generator=false
- twoArgumentPooler @2803-2812; FunctionExpression; parameters=2; async=false; generator=false
- threeArgumentPooler @2814-2823; FunctionExpression; parameters=3; async=false; generator=false
- fiveArgumentPooler @2825-2834; FunctionExpression; parameters=5; async=false; generator=false
- standardReleaser @2836-2844; FunctionExpression; parameters=1; async=false; generator=false
- addPoolingTo @2858-2867; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2879-2929; FunctionExpression; parameters=3; async=false; generator=false
- initializeTouchEvents @2914-2916; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2929-3507; FunctionExpression; parameters=3; async=false; generator=false
- validateExplicitKey @3007-3039; FunctionDeclaration; parameters=1; async=false; generator=false
- validateChildKeys @3049-3061; FunctionDeclaration; parameters=1; async=false; generator=false
- isValidComponent @3095-3101; FunctionExpression; parameters=1; async=false; generator=false
- getKey @3111-3118; FunctionExpression; parameters=2; async=false; generator=false
- setDOMOperations @3145-3147; FunctionExpression; parameters=1; async=false; generator=false
- setReactReconcileTransaction @3153-3155; FunctionExpression; parameters=1; async=false; generator=false
- isMounted @3171-3173; FunctionExpression; parameters=0; async=false; generator=false
- getDOMNode @3182-3188; FunctionExpression; parameters=0; async=false; generator=false
- setProps @3198-3204; FunctionExpression; parameters=2; async=false; generator=false
- replaceProps @3214-3225; FunctionExpression; parameters=2; async=false; generator=false
- construct @3237-3264; FunctionExpression; parameters=2; async=false; generator=false
- mountComponent @3279-3292; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @3304-3316; FunctionExpression; parameters=0; async=false; generator=false
- receiveProps @3328-3335; FunctionExpression; parameters=2; async=false; generator=false
- performUpdateIfNecessary @3343-3347; FunctionExpression; parameters=0; async=false; generator=false
- _performUpdateIfNecessary @3355-3363; FunctionExpression; parameters=1; async=false; generator=false
- updateComponent @3372-3388; FunctionExpression; parameters=2; async=false; generator=false
- mountComponentIntoNode @3400-3411; FunctionExpression; parameters=3; async=false; generator=false
- _mountComponentIntoNode @3421-3455; FunctionExpression; parameters=4; async=false; generator=false
- unmountComponentFromNode @3465-3471; FunctionExpression; parameters=1; async=false; generator=false
- isOwnedBy @3481-3483; FunctionExpression; parameters=1; async=false; generator=false
- getSiblingByRef @3493-3499; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3507-4425; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @3508-4424; FunctionExpression; parameters=0; async=false; generator=false
- displayName @3778-3780; FunctionExpression; parameters=2; async=false; generator=false
- mixins @3781-3787; FunctionExpression; parameters=2; async=false; generator=false
- propTypes @3788-3790; FunctionExpression; parameters=2; async=false; generator=false
- validateMethodOverride @3793-3817; FunctionDeclaration; parameters=2; async=false; generator=false
- validateLifeCycleOnReplaceState @3820-3833; FunctionDeclaration; parameters=1; async=false; generator=false
- mixSpecIntoComponent @3839-3882; FunctionDeclaration; parameters=2; async=false; generator=false
- createChainedFunction @3892-3897; FunctionDeclaration; parameters=2; async=false; generator=false
- chainedFunction @3893-3896; FunctionExpression; parameters=0; async=false; generator=false
- construct @3961-3967; FunctionExpression; parameters=2; async=false; generator=false
- isMounted @3975-3978; FunctionExpression; parameters=0; async=false; generator=false
- mountComponent @3989-4023; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @4031-4052; FunctionExpression; parameters=0; async=false; generator=false
- setState @4071-4077; FunctionExpression; parameters=2; async=false; generator=false
- replaceState @4091-4095; FunctionExpression; parameters=2; async=false; generator=false
- _processProps @4104-4122; FunctionExpression; parameters=1; async=false; generator=false
- performUpdateIfNecessary @4124-4133; FunctionExpression; parameters=0; async=false; generator=false
- _performUpdateIfNecessary @4142-4180; FunctionExpression; parameters=1; async=false; generator=false
- _performComponentUpdate @4191-4210; FunctionExpression; parameters=3; async=false; generator=false
- updateComponent @4224-4242; FunctionExpression; parameters=3; async=false; generator=false
- forceUpdate @4258-4274; FunctionExpression; parameters=1; async=false; generator=false
- _renderValidatedComponent @4279-4296; FunctionExpression; parameters=0; async=false; generator=false
- _bindAutoBindMethods @4301-4309; FunctionExpression; parameters=0; async=false; generator=false
- _bindAutoBindMethod @4317-4346; FunctionExpression; parameters=1; async=false; generator=false
- boundMethod @4319-4321; FunctionExpression; parameters=0; async=false; generator=false
- boundMethod.bind @4325-4343; FunctionExpression; parameters=1; async=false; generator=false
- ReactCompositeComponentBase @4349-4349; FunctionExpression; parameters=0; async=false; generator=false
- createClass @4376-4400; FunctionExpression; parameters=1; async=false; generator=false
- Constructor @4377-4377; FunctionExpression; parameters=0; async=false; generator=false
- ConvenienceConstructor @4392-4396; FunctionExpression; parameters=2; async=false; generator=false
- autoBind @4410-4419; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4425-4466; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @4466-4661; FunctionExpression; parameters=3; async=false; generator=false
- createDOMComponentClass @4508-4520; FunctionDeclaration; parameters=2; async=false; generator=false
- Constructor @4509-4509; FunctionExpression; parameters=0; async=false; generator=false
- ConvenienceConstructor @4513-4517; FunctionExpression; parameters=2; async=false; generator=false
- injectComponentClasses @4652-4654; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4661-4715; FunctionExpression; parameters=3; async=false; generator=false
- render @4697-4702; FunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @4704-4710; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4715-4895; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @4716-4894; FunctionExpression; parameters=0; async=false; generator=false
- updatePropertyByID @4782-4790; FunctionExpression; parameters=3; async=false; generator=false
- deletePropertyByID @4800-4808; FunctionExpression; parameters=3; async=false; generator=false
- updatePropertiesByID @4820-4827; FunctionExpression; parameters=2; async=false; generator=false
- updateStylesByID @4837-4840; FunctionExpression; parameters=2; async=false; generator=false
- updateInnerHTMLByID @4849-4854; FunctionExpression; parameters=2; async=false; generator=false
- updateTextContentByID @4863-4866; FunctionExpression; parameters=2; async=false; generator=false
- dangerouslyReplaceNodeWithMarkupByID @4876-4879; FunctionExpression; parameters=2; async=false; generator=false
- manageChildrenByParentID @4885-4888; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @4895-5012; FunctionExpression; parameters=3; async=false; generator=false
- getInitialState @4943-4948; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @4950-4953; FunctionExpression; parameters=0; async=false; generator=false
- getChecked @4955-4957; FunctionExpression; parameters=0; async=false; generator=false
- getValue @4959-4962; FunctionExpression; parameters=0; async=false; generator=false
- render @4964-4973; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @4975-4992; FunctionExpression; parameters=3; async=false; generator=false
- handleChange @4994-5006; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5012-5064; FunctionExpression; parameters=3; async=false; generator=false
- componentWillMount @5044-5054; FunctionExpression; parameters=0; async=false; generator=false
- render @5056-5058; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5064-5224; FunctionExpression; parameters=3; async=false; generator=false
- selectValueType @5098-5117; FunctionDeclaration; parameters=3; async=false; generator=false
- updateOptions @5123-5140; FunctionDeclaration; parameters=0; async=false; generator=false
- getInitialState @5164-5166; FunctionExpression; parameters=0; async=false; generator=false
- componentWillReceiveProps @5168-5174; FunctionExpression; parameters=1; async=false; generator=false
- shouldComponentUpdate @5176-5179; FunctionExpression; parameters=0; async=false; generator=false
- render @5181-5189; FunctionExpression; parameters=0; async=false; generator=false
- handleChange @5195-5218; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5224-5364; FunctionExpression; parameters=3; async=false; generator=false
- getInitialState @5275-5311; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @5313-5316; FunctionExpression; parameters=0; async=false; generator=false
- getValue @5318-5320; FunctionExpression; parameters=0; async=false; generator=false
- render @5322-5337; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @5339-5347; FunctionExpression; parameters=3; async=false; generator=false
- handleChange @5349-5358; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5364-5434; FunctionExpression; parameters=3; async=false; generator=false
- inject @5402-5428; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @5434-5783; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @5435-5782; FunctionExpression; parameters=0; async=false; generator=false
- trapBubbledEvent @5526-5534; FunctionDeclaration; parameters=3; async=false; generator=false
- trapCapturedEvent @5544-5552; FunctionDeclaration; parameters=3; async=false; generator=false
- registerScrollValueMonitoring @5563-5567; FunctionDeclaration; parameters=0; async=false; generator=false
- listenAtTopLevel @5591-5666; FunctionDeclaration; parameters=1; async=false; generator=false
- ensureListening @5696-5708; FunctionExpression; parameters=2; async=false; generator=false
- setEnabled @5715-5724; FunctionExpression; parameters=1; async=false; generator=false
- isEnabled @5729-5734; FunctionExpression; parameters=0; async=false; generator=false
- handleTopLevel @5745-5762; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @5758-5761; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5783-5877; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @5784-5876; FunctionExpression; parameters=0; async=false; generator=false
- setEnabled @5829-5831; FunctionExpression; parameters=1; async=false; generator=false
- isEnabled @5836-5838; FunctionExpression; parameters=0; async=false; generator=false
- createTopLevelCallback @5849-5870; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5850-5869; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5877-6045; FunctionExpression; parameters=3; async=false; generator=false
- getID @5914-5934; FunctionDeclaration; parameters=1; async=false; generator=false
- internalGetID @5936-5944; FunctionDeclaration; parameters=1; async=false; generator=false
- setID @5952-5959; FunctionDeclaration; parameters=2; async=false; generator=false
- getNode @5968-5973; FunctionDeclaration; parameters=1; async=false; generator=false
- isValid @5985-6000; FunctionDeclaration; parameters=2; async=false; generator=false
- contains @6002-6027; FunctionDeclaration; parameters=2; async=false; generator=false
- purgeID @6034-6036; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @6045-6231; FunctionExpression; parameters=3; async=false; generator=false
- getActiveElement @6068-6073; FunctionDeclaration; parameters=0; async=false; generator=false
- isInDocument @6075-6077; FunctionDeclaration; parameters=1; async=false; generator=false
- hasSelectionCapabilities @6087-6093; FunctionExpression; parameters=1; async=false; generator=false
- getSelectionInformation @6095-6104; FunctionExpression; parameters=0; async=false; generator=false
- restoreSelection @6111-6125; FunctionExpression; parameters=1; async=false; generator=false
- getSelection @6132-6178; FunctionExpression; parameters=1; async=false; generator=false
- setSelection @6186-6225; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6231-6640; FunctionExpression; parameters=3; async=false; generator=false
- getReactRootIDString @6281-6283; FunctionDeclaration; parameters=1; async=false; generator=false
- isBoundary @6293-6295; FunctionDeclaration; parameters=2; async=false; generator=false
- isValidID @6304-6308; FunctionDeclaration; parameters=1; async=false; generator=false
- isAncestorIDOf @6318-6323; FunctionDeclaration; parameters=2; async=false; generator=false
- getParentID @6332-6334; FunctionDeclaration; parameters=1; async=false; generator=false
- getNextDescendantID @6345-6371; FunctionDeclaration; parameters=2; async=false; generator=false
- getFirstCommonAncestorID @6384-6407; FunctionDeclaration; parameters=2; async=false; generator=false
- traverseParentPath @6420-6454; FunctionDeclaration; parameters=6; async=false; generator=false
- createReactRootID @6467-6471; FunctionExpression; parameters=0; async=false; generator=false
- isRenderedByReact @6480-6487; FunctionExpression; parameters=1; async=false; generator=false
- getFirstReactDOM @6497-6506; FunctionExpression; parameters=1; async=false; generator=false
- findComponentRoot @6517-6568; FunctionExpression; parameters=2; async=false; generator=false
- getReactRootIDFromNodeID @6578-6581; FunctionExpression; parameters=1; async=false; generator=false
- traverseEnterLeave @6597-6605; FunctionExpression; parameters=5; async=false; generator=false
- traverseTwoPhase @6617-6622; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @6640-6987; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @6641-6986; FunctionExpression; parameters=0; async=false; generator=false
- getReactRootElementInContainer @6684-6686; FunctionDeclaration; parameters=1; async=false; generator=false
- getReactRootID @6692-6695; FunctionDeclaration; parameters=1; async=false; generator=false
- scrollMonitor @6731-6733; FunctionExpression; parameters=2; async=false; generator=false
- prepareTopLevelEvents @6742-6747; FunctionExpression; parameters=1; async=false; generator=false
- _updateRootComponent @6756-6773; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @6762-6764; FunctionExpression; parameters=0; async=false; generator=false
- _registerComponent @6781-6787; FunctionExpression; parameters=2; async=false; generator=false
- _renderNewRootComponent @6796-6814; FunctionExpression; parameters=3; async=false; generator=false
- renderComponent @6828-6858; FunctionExpression; parameters=3; async=false; generator=false
- constructAndRenderComponent @6869-6871; FunctionExpression; parameters=3; async=false; generator=false
- constructAndRenderComponentByID @6882-6884; FunctionExpression; parameters=3; async=false; generator=false
- registerContainer @6894-6906; FunctionExpression; parameters=1; async=false; generator=false
- unmountAndReleaseReactRootNode @6915-6928; FunctionExpression; parameters=1; async=false; generator=false
- findReactContainerForID @6937-6969; FunctionExpression; parameters=1; async=false; generator=false
- findReactNodeByID @6977-6980; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6987-7197; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @6988-7196; FunctionExpression; parameters=0; async=false; generator=false
- shouldManageExisting @7018-7020; FunctionDeclaration; parameters=2; async=false; generator=false
- enqueueMarkupAt @7038-7041; FunctionExpression; parameters=2; async=false; generator=false
- enqueueMove @7043-7046; FunctionExpression; parameters=2; async=false; generator=false
- enqueueUnmountChildByName @7048-7055; FunctionExpression; parameters=2; async=false; generator=false
- processChildDOMOperationsQueue @7066-7072; FunctionExpression; parameters=0; async=false; generator=false
- unmountMultiChild @7074-7083; FunctionExpression; parameters=0; async=false; generator=false
- mountMultiChild @7097-7114; FunctionExpression; parameters=2; async=false; generator=false
- updateMultiChild @7130-7187; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @7197-7560; FunctionExpression; parameters=3; async=false; generator=false
- assertValidProps @7247-7261; FunctionDeclaration; parameters=1; async=false; generator=false
- ReactNativeComponent @7268-7272; FunctionDeclaration; parameters=2; async=false; generator=false
- mountComponent @7285-7293; FunctionExpression; parameters=2; async=false; generator=false
- _createOpenTagMarkup @7306-7337; FunctionExpression; parameters=0; async=false; generator=false
- _createContentMarkup @7346-7367; FunctionExpression; parameters=1; async=false; generator=false
- receiveProps @7369-7372; FunctionExpression; parameters=2; async=false; generator=false
- updateComponent @7383-7387; FunctionExpression; parameters=2; async=false; generator=false
- _updateDOMProperties @7403-7494; FunctionExpression; parameters=1; async=false; generator=false
- _updateDOMChildren @7503-7538; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @7546-7550; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7560-7657; FunctionExpression; parameters=3; async=false; generator=false
- ReactOnDOMReady @7597-7599; FunctionDeclaration; parameters=1; async=false; generator=false
- enqueue @7611-7614; FunctionExpression; parameters=2; async=false; generator=false
- notifyAll @7622-7633; FunctionExpression; parameters=0; async=false; generator=false
- reset @7640-7642; FunctionExpression; parameters=0; async=false; generator=false
- destructor @7647-7649; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7657-7805; FunctionExpression; parameters=3; async=false; generator=false
- isValidOwner @7717-7723; FunctionExpression; parameters=1; async=false; generator=false
- addComponentAsRefTo @7734-7740; FunctionExpression; parameters=3; async=false; generator=false
- removeComponentAsRefFrom @7751-7761; FunctionExpression; parameters=3; async=false; generator=false
- attachRef @7778-7786; FunctionExpression; parameters=2; async=false; generator=false
- detachRef @7795-7797; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7805-7925; FunctionExpression; parameters=3; async=false; generator=false
- createTransferStrategy @7837-7845; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @7838-7844; FunctionExpression; parameters=3; async=false; generator=false
- transferPropsTo @7897-7917; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7925-8085; FunctionExpression; parameters=3; async=false; generator=false
- createPrimitiveTypeChecker @8014-8030; FunctionDeclaration; parameters=1; async=false; generator=false
- validatePrimitiveType @8015-8028; FunctionDeclaration; parameters=3; async=false; generator=false
- createEnumTypeChecker @8032-8044; FunctionDeclaration; parameters=1; async=false; generator=false
- validateEnumType @8034-8042; FunctionDeclaration; parameters=3; async=false; generator=false
- createInstanceTypeChecker @8046-8057; FunctionDeclaration; parameters=1; async=false; generator=false
- validateInstanceType @8047-8055; FunctionDeclaration; parameters=3; async=false; generator=false
- createChainableTypeChecker @8059-8081; FunctionDeclaration; parameters=1; async=false; generator=false
- createTypeChecker @8060-8079; FunctionDeclaration; parameters=1; async=false; generator=false
- checkType @8061-8074; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @8085-8248; FunctionExpression; parameters=3; async=false; generator=false
- initialize @8141-8145; FunctionExpression; parameters=0; async=false; generator=false
- close @8151-8153; FunctionExpression; parameters=1; async=false; generator=false
- initialize @8164-8166; FunctionExpression; parameters=0; async=false; generator=false
- close @8171-8173; FunctionExpression; parameters=0; async=false; generator=false
- ReactReconcileTransaction @8201-8204; FunctionDeclaration; parameters=0; async=false; generator=false
- getTransactionWrappers @8214-8220; FunctionExpression; parameters=0; async=false; generator=false
- getReactOnDOMReady @8226-8228; FunctionExpression; parameters=0; async=false; generator=false
- destructor @8234-8237; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8248-8295; FunctionExpression; parameters=3; async=false; generator=false
- renderComponentToString @8276-8289; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8283-8285; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8295-8383; FunctionExpression; parameters=3; async=false; generator=false
- ReactTextComponent @8338-8340; FunctionExpression; parameters=1; async=false; generator=false
- mountComponent @8353-8360; FunctionExpression; parameters=1; async=false; generator=false
- receiveProps @8369-8377; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @8383-8490; FunctionExpression; parameters=3; async=false; generator=false
- batchedUpdates @8414-8452; FunctionDeclaration; parameters=1; async=false; generator=false
- enqueueUpdate @8458-8481; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8490-8827; FunctionExpression; parameters=3; async=false; generator=false
- executeDispatch @8736-8742; FunctionExpression; parameters=3; async=false; generator=false
- extractEvents @8752-8821; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @8827-8986; FunctionExpression; parameters=3; async=false; generator=false
- timeStamp @8867-8869; FunctionExpression; parameters=1; async=false; generator=false
- SyntheticEvent @8891-8912; FunctionDeclaration; parameters=3; async=false; generator=false
- preventDefault @8916-8921; FunctionExpression; parameters=0; async=false; generator=false
- stopPropagation @8923-8927; FunctionExpression; parameters=0; async=false; generator=false
- persist @8934-8936; FunctionExpression; parameters=0; async=false; generator=false
- destructor @8948-8956; FunctionExpression; parameters=0; async=false; generator=false
- SyntheticEvent.augmentClass @8968-8980; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @8986-9032; FunctionExpression; parameters=3; async=false; generator=false
- SyntheticFocusEvent @9024-9026; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9032-9090; FunctionExpression; parameters=3; async=false; generator=false
- SyntheticKeyboardEvent @9082-9084; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9090-9177; FunctionExpression; parameters=3; async=false; generator=false
- button @9128-9141; FunctionExpression; parameters=1; async=false; generator=false
- relatedTarget @9143-9149; FunctionExpression; parameters=1; async=false; generator=false
- pageX @9151-9155; FunctionExpression; parameters=1; async=false; generator=false
- pageY @9156-9160; FunctionExpression; parameters=1; async=false; generator=false
- SyntheticMouseEvent @9169-9171; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9177-9227; FunctionExpression; parameters=3; async=false; generator=false
- SyntheticMutationEvent @9219-9221; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9227-9279; FunctionExpression; parameters=3; async=false; generator=false
- SyntheticTouchEvent @9271-9273; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9279-9326; FunctionExpression; parameters=3; async=false; generator=false
- SyntheticUIEvent @9318-9320; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9326-9391; FunctionExpression; parameters=3; async=false; generator=false
- deltaX @9355-9362; FunctionExpression; parameters=1; async=false; generator=false
- deltaY @9363-9372; FunctionExpression; parameters=1; async=false; generator=false
- SyntheticWheelEvent @9383-9385; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9391-9646; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @9392-9645; FunctionExpression; parameters=0; async=false; generator=false
- reinitializeTransaction @9502-9524; FunctionExpression; parameters=0; async=false; generator=false
- isInTransaction @9534-9536; FunctionExpression; parameters=0; async=false; generator=false
- perform @9549-9572; FunctionExpression; parameters=8; async=false; generator=false
- initializeAll @9574-9597; FunctionExpression; parameters=0; async=false; generator=false
- closeAll @9605-9631; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9646-9684; FunctionExpression; parameters=3; async=false; generator=false
- refreshScrollValues @9673-9678; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9684-9756; FunctionExpression; parameters=3; async=false; generator=false
- accumulate @9725-9752; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9756-9812; FunctionExpression; parameters=3; async=false; generator=false
- copyProperties @9782-9808; FunctionDeclaration; parameters=7; async=false; generator=false
- (anonymous) @9812-9877; FunctionExpression; parameters=3; async=false; generator=false
- createObjectFrom @9856-9873; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9877-9936; FunctionExpression; parameters=3; async=false; generator=false
- dangerousStyleValue @9910-9932; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9936-9981; FunctionExpression; parameters=3; async=false; generator=false
- makeEmptyFunction @9957-9961; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @9958-9960; FunctionExpression; parameters=0; async=false; generator=false
- emptyFunction @9968-9968; FunctionDeclaration; parameters=0; async=false; generator=false
- thatReturnsThis @9975-9975; FunctionExpression; parameters=0; async=false; generator=false
- thatReturnsArgument @9976-9976; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9981-10044; FunctionExpression; parameters=3; async=false; generator=false
- escaper @10021-10023; FunctionDeclaration; parameters=1; async=false; generator=false
- escapeTextForBrowser @10025-10040; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10044-10095; FunctionExpression; parameters=3; async=false; generator=false
- ex @10076-10088; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10077-10079; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10095-10151; FunctionExpression; parameters=3; async=false; generator=false
- flattenSingleChildIntoContext @10124-10134; FunctionDeclaration; parameters=3; async=false; generator=false
- flattenChildren @10140-10147; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10151-10189; FunctionExpression; parameters=3; async=false; generator=false
- forEachAccumulated @10179-10185; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @10189-10267; FunctionExpression; parameters=3; async=false; generator=false
- ge @10217-10221; FunctionDeclaration; parameters=3; async=false; generator=false
- _geFromSubtree @10223-10251; FunctionDeclaration; parameters=3; async=false; generator=false
- _getNodeID @10259-10263; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10267-10311; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @10268-10310; FunctionExpression; parameters=0; async=false; generator=false
- getEventTarget @10298-10306; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10311-10353; FunctionExpression; parameters=3; async=false; generator=false
- getTextContentAccessor @10342-10349; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @10353-10410; FunctionExpression; parameters=3; async=false; generator=false
- hasArrayNature @10385-10406; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10410-10447; FunctionExpression; parameters=3; async=false; generator=false
- hyphenate @10441-10443; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10447-10495; FunctionExpression; parameters=3; async=false; generator=false
- insertNodeAt @10474-10491; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @10495-10551; FunctionExpression; parameters=3; async=false; generator=false
- invariant @10524-10528; FunctionDeclaration; parameters=1; async=false; generator=false
- invariantDev @10533-10546; FunctionExpression; parameters=8; async=false; generator=false
- (anonymous) @10543-10543; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10551-10627; FunctionExpression; parameters=3; async=false; generator=false
- isEventSupported @10598-10623; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @10627-10673; FunctionExpression; parameters=3; async=false; generator=false
- joinClasses @10656-10669; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10673-10731; FunctionExpression; parameters=3; async=false; generator=false
- keyMirror @10714-10727; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10731-10774; FunctionExpression; parameters=3; async=false; generator=false
- keyOf @10760-10769; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10774-10815; FunctionExpression; parameters=3; async=false; generator=false
- memoizeStringOnly @10802-10811; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10804-10810; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10815-10854; FunctionExpression; parameters=3; async=false; generator=false
- merge @10845-10850; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @10854-11018; FunctionExpression; parameters=3; async=false; generator=false
- isTerminal @10927-10929; FunctionExpression; parameters=1; async=false; generator=false
- normalizeMergeArg @10943-10945; FunctionExpression; parameters=1; async=false; generator=false
- checkMergeArrayArgs @10955-10960; FunctionExpression; parameters=2; async=false; generator=false
- checkMergeObjectArgs @10966-10969; FunctionExpression; parameters=2; async=false; generator=false
- checkMergeObjectArg @10974-10976; FunctionExpression; parameters=1; async=false; generator=false
- checkMergeLevel @10984-10986; FunctionExpression; parameters=1; async=false; generator=false
- checkArrayStrategy @10994-10999; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11018-11065; FunctionExpression; parameters=3; async=false; generator=false
- mergeInto @11050-11061; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @11065-11101; FunctionExpression; parameters=3; async=false; generator=false
- mixInto @11089-11097; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @11101-11150; FunctionExpression; parameters=3; async=false; generator=false
- objMapKeyVal @11134-11146; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @11150-11179; FunctionExpression; parameters=3; async=false; generator=false
- throwIf @11171-11175; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @11179-11326; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @11180-11325; FunctionExpression; parameters=0; async=false; generator=false
- traverseAllChildrenImpl @11238-11294; FunctionExpression; parameters=5; async=false; generator=false
- traverseAllChildren @11311-11315; FunctionDeclaration; parameters=3; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/react/react.min.js

Blob: `a631c5bd91438c615b4d8be8d37de7f21460c467`. Role: imported-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-19; FunctionExpression; parameters=0; async=false; generator=false
- updatePropertyByID @18-19; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- componentDidMount @18-18; FunctionExpression; parameters=1; async=false; generator=false
- render @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- injectComponentClasses @18-18; FunctionExpression; parameters=1; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- o @18-18; FunctionExpression; parameters=0; async=false; generator=false
- n @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- autoBind @18-18; FunctionExpression; parameters=1; async=false; generator=false
- createClass @18-18; FunctionExpression; parameters=1; async=false; generator=false
- r @18-18; FunctionExpression; parameters=0; async=false; generator=false
- t @18-18; FunctionExpression; parameters=0; async=false; generator=false
- E @18-18; FunctionExpression; parameters=0; async=false; generator=false
- _bindAutoBindMethod @18-18; FunctionExpression; parameters=1; async=false; generator=false
- n @18-18; FunctionExpression; parameters=0; async=false; generator=false
- _bindAutoBindMethods @18-18; FunctionExpression; parameters=0; async=false; generator=false
- _renderValidatedComponent @18-18; FunctionExpression; parameters=0; async=false; generator=false
- forceUpdate @18-18; FunctionExpression; parameters=1; async=false; generator=false
- updateComponent @18-18; FunctionExpression; parameters=2; async=false; generator=false
- _performComponentUpdate @18-18; FunctionExpression; parameters=3; async=false; generator=false
- _performUpdateIfNecessary @18-18; FunctionExpression; parameters=1; async=false; generator=false
- performUpdateIfNecessary @18-18; FunctionExpression; parameters=0; async=false; generator=false
- _processProps @18-18; FunctionExpression; parameters=1; async=false; generator=false
- replaceState @18-18; FunctionExpression; parameters=2; async=false; generator=false
- setState @18-18; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @18-18; FunctionExpression; parameters=0; async=false; generator=false
- mountComponent @18-18; FunctionExpression; parameters=2; async=false; generator=false
- isMounted @18-18; FunctionExpression; parameters=0; async=false; generator=false
- construct @18-18; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @18-18; FunctionExpression; parameters=2; async=false; generator=false
- mixins @18-18; FunctionExpression; parameters=2; async=false; generator=false
- displayName @18-18; FunctionExpression; parameters=2; async=false; generator=false
- i @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- getSiblingByRef @18-18; FunctionExpression; parameters=1; async=false; generator=false
- isOwnedBy @18-18; FunctionExpression; parameters=1; async=false; generator=false
- unmountComponentFromNode @18-18; FunctionExpression; parameters=1; async=false; generator=false
- _mountComponentIntoNode @18-18; FunctionExpression; parameters=4; async=false; generator=false
- mountComponentIntoNode @18-18; FunctionExpression; parameters=3; async=false; generator=false
- updateComponent @18-18; FunctionExpression; parameters=2; async=false; generator=false
- _performUpdateIfNecessary @18-18; FunctionExpression; parameters=1; async=false; generator=false
- performUpdateIfNecessary @18-18; FunctionExpression; parameters=0; async=false; generator=false
- receiveProps @18-18; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @18-18; FunctionExpression; parameters=0; async=false; generator=false
- mountComponent @18-18; FunctionExpression; parameters=1; async=false; generator=false
- construct @18-18; FunctionExpression; parameters=2; async=false; generator=false
- replaceProps @18-18; FunctionExpression; parameters=2; async=false; generator=false
- setProps @18-18; FunctionExpression; parameters=2; async=false; generator=false
- getDOMNode @18-18; FunctionExpression; parameters=0; async=false; generator=false
- isMounted @18-18; FunctionExpression; parameters=0; async=false; generator=false
- setReactReconcileTransaction @18-18; FunctionExpression; parameters=1; async=false; generator=false
- setDOMOperations @18-18; FunctionExpression; parameters=1; async=false; generator=false
- getKey @18-18; FunctionExpression; parameters=2; async=false; generator=false
- isValidComponent @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- initializeTouchEvents @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- l @18-18; FunctionExpression; parameters=2; async=false; generator=false
- a @18-18; FunctionExpression; parameters=1; async=false; generator=false
- i @18-18; FunctionExpression; parameters=5; async=false; generator=false
- o @18-18; FunctionExpression; parameters=3; async=false; generator=false
- r @18-18; FunctionExpression; parameters=2; async=false; generator=false
- n @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- validate @18-18; FunctionExpression; parameters=0; async=false; generator=false
- injectInstanceHandle @18-18; FunctionExpression; parameters=1; async=false; generator=false
- l @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- u @18-18; FunctionDeclaration; parameters=4; async=false; generator=false
- s @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- a @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- i @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- c @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- l @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- u @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- s @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- a @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- i @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- _resetEventPlugins @18-18; FunctionExpression; parameters=0; async=false; generator=false
- getPluginModuleForEvent @18-18; FunctionExpression; parameters=1; async=false; generator=false
- injectEventPluginsByName @18-18; FunctionExpression; parameters=1; async=false; generator=false
- injectEventPluginOrder @18-18; FunctionExpression; parameters=1; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- processEventQueue @18-18; FunctionExpression; parameters=0; async=false; generator=false
- enqueueEvents @18-18; FunctionExpression; parameters=1; async=false; generator=false
- extractEvents @18-18; FunctionExpression; parameters=4; async=false; generator=false
- p @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- capture @18-18; FunctionExpression; parameters=3; async=false; generator=false
- listen @18-18; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- extractEvents @18-18; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- className @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- a @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- i @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- deleteValueForProperty @18-18; FunctionExpression; parameters=2; async=false; generator=false
- setValueForProperty @18-18; FunctionExpression; parameters=3; async=false; generator=false
- createMarkupForProperty @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- getDefaultValueForProperty @18-18; FunctionExpression; parameters=2; async=false; generator=false
- isCustomAttribute @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=1; async=false; generator=false
- injectDOMPropertyConfig @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- p @18-18; FunctionExpression; parameters=2; async=false; generator=false
- c @18-18; FunctionExpression; parameters=3; async=false; generator=false
- l @18-18; FunctionExpression; parameters=2; async=false; generator=false
- u @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- extractEvents @18-18; FunctionExpression; parameters=4; async=false; generator=false
- set @18-18; FunctionExpression; parameters=1; async=false; generator=false
- get @18-18; FunctionExpression; parameters=0; async=false; generator=false
- m @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- v @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- f @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- h @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- d @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- p @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- c @18-18; FunctionDeclaration; parameters=0; async=false; generator=false
- l @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- u @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- s @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- a @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- i @18-18; FunctionDeclaration; parameters=0; async=false; generator=false
- o @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- __purge @18-18; FunctionExpression; parameters=0; async=false; generator=false
- deleteAllListeners @18-18; FunctionExpression; parameters=1; async=false; generator=false
- deleteListener @18-18; FunctionExpression; parameters=2; async=false; generator=false
- getListener @18-18; FunctionExpression; parameters=2; async=false; generator=false
- putListener @18-18; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- setValueForStyles @18-18; FunctionExpression; parameters=2; async=false; generator=false
- createMarkupForStyles @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=2; async=false; generator=false
- n @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=3; async=false; generator=false
- r @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-20; FunctionExpression; parameters=2; async=false; generator=false
- n.augmentClass @19-20; FunctionExpression; parameters=2; async=false; generator=false
- destructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- persist @19-19; FunctionExpression; parameters=0; async=false; generator=false
- stopPropagation @19-19; FunctionExpression; parameters=0; async=false; generator=false
- preventDefault @19-19; FunctionExpression; parameters=0; async=false; generator=false
- timeStamp @19-19; FunctionExpression; parameters=1; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- extractEvents @19-19; FunctionExpression; parameters=4; async=false; generator=false
- executeDispatch @19-19; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- receiveProps @19-19; FunctionExpression; parameters=1; async=false; generator=false
- mountComponent @19-19; FunctionExpression; parameters=1; async=false; generator=false
- a @19-19; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- destructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getReactOnDOMReady @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getTransactionWrappers @19-19; FunctionExpression; parameters=0; async=false; generator=false
- close @19-19; FunctionExpression; parameters=0; async=false; generator=false
- initialize @19-19; FunctionExpression; parameters=0; async=false; generator=false
- close @19-19; FunctionExpression; parameters=1; async=false; generator=false
- initialize @19-19; FunctionExpression; parameters=0; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- i @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- t @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=3; async=false; generator=false
- o @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- t @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- t @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- t @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- transferPropsTo @19-19; FunctionExpression; parameters=1; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- detachRef @19-19; FunctionExpression; parameters=1; async=false; generator=false
- attachRef @19-19; FunctionExpression; parameters=2; async=false; generator=false
- removeComponentAsRefFrom @19-19; FunctionExpression; parameters=3; async=false; generator=false
- addComponentAsRefTo @19-19; FunctionExpression; parameters=3; async=false; generator=false
- isValidOwner @19-19; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- destructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- reset @19-19; FunctionExpression; parameters=0; async=false; generator=false
- notifyAll @19-19; FunctionExpression; parameters=0; async=false; generator=false
- enqueue @19-19; FunctionExpression; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- unmountComponent @19-19; FunctionExpression; parameters=0; async=false; generator=false
- _updateDOMChildren @19-19; FunctionExpression; parameters=2; async=false; generator=false
- _updateDOMProperties @19-19; FunctionExpression; parameters=1; async=false; generator=false
- updateComponent @19-19; FunctionExpression; parameters=2; async=false; generator=false
- receiveProps @19-19; FunctionExpression; parameters=2; async=false; generator=false
- _createContentMarkup @19-19; FunctionExpression; parameters=1; async=false; generator=false
- _createOpenTagMarkup @19-19; FunctionExpression; parameters=0; async=false; generator=false
- mountComponent @19-19; FunctionExpression; parameters=2; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- updateMultiChild @19-19; FunctionExpression; parameters=2; async=false; generator=false
- mountMultiChild @19-19; FunctionExpression; parameters=2; async=false; generator=false
- unmountMultiChild @19-19; FunctionExpression; parameters=0; async=false; generator=false
- processChildDOMOperationsQueue @19-19; FunctionExpression; parameters=0; async=false; generator=false
- enqueueUnmountChildByName @19-19; FunctionExpression; parameters=2; async=false; generator=false
- enqueueMove @19-19; FunctionExpression; parameters=2; async=false; generator=false
- enqueueMarkupAt @19-19; FunctionExpression; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- findReactNodeByID @19-19; FunctionExpression; parameters=1; async=false; generator=false
- findReactContainerForID @19-19; FunctionExpression; parameters=1; async=false; generator=false
- unmountAndReleaseReactRootNode @19-19; FunctionExpression; parameters=1; async=false; generator=false
- registerContainer @19-19; FunctionExpression; parameters=1; async=false; generator=false
- constructAndRenderComponentByID @19-19; FunctionExpression; parameters=3; async=false; generator=false
- constructAndRenderComponent @19-19; FunctionExpression; parameters=3; async=false; generator=false
- renderComponent @19-19; FunctionExpression; parameters=3; async=false; generator=false
- _renderNewRootComponent @19-19; FunctionExpression; parameters=3; async=false; generator=false
- _registerComponent @19-19; FunctionExpression; parameters=2; async=false; generator=false
- _updateRootComponent @19-19; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- prepareTopLevelEvents @19-19; FunctionExpression; parameters=1; async=false; generator=false
- scrollMonitor @19-19; FunctionExpression; parameters=2; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- traverseTwoPhase @19-19; FunctionExpression; parameters=3; async=false; generator=false
- traverseEnterLeave @19-19; FunctionExpression; parameters=5; async=false; generator=false
- getReactRootIDFromNodeID @19-19; FunctionExpression; parameters=1; async=false; generator=false
- findComponentRoot @19-19; FunctionExpression; parameters=2; async=false; generator=false
- getFirstReactDOM @19-19; FunctionExpression; parameters=1; async=false; generator=false
- isRenderedByReact @19-19; FunctionExpression; parameters=1; async=false; generator=false
- createReactRootID @19-19; FunctionExpression; parameters=0; async=false; generator=false
- l @19-19; FunctionDeclaration; parameters=6; async=false; generator=false
- u @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- s @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- a @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- i @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- o @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- setSelection @19-19; FunctionExpression; parameters=2; async=false; generator=false
- getSelection @19-19; FunctionExpression; parameters=1; async=false; generator=false
- restoreSelection @19-19; FunctionExpression; parameters=1; async=false; generator=false
- getSelectionInformation @19-19; FunctionExpression; parameters=0; async=false; generator=false
- hasSelectionCapabilities @19-19; FunctionExpression; parameters=1; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=3; async=false; generator=false
- l @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- u @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- s @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- a @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- i @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- o @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- createTopLevelCallback @19-19; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=1; async=false; generator=false
- isEnabled @19-19; FunctionExpression; parameters=0; async=false; generator=false
- setEnabled @19-19; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- handleTopLevel @19-19; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @19-19; FunctionExpression; parameters=0; async=false; generator=false
- setEnabled @19-19; FunctionExpression; parameters=1; async=false; generator=false
- ensureListening @19-19; FunctionExpression; parameters=2; async=false; generator=false
- i @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- o @19-19; FunctionDeclaration; parameters=0; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=3; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- handleChange @19-19; FunctionExpression; parameters=1; async=false; generator=false
- componentDidUpdate @19-19; FunctionExpression; parameters=3; async=false; generator=false
- render @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getValue @19-19; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getInitialState @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- handleChange @19-19; FunctionExpression; parameters=1; async=false; generator=false
- render @19-19; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @19-19; FunctionExpression; parameters=0; async=false; generator=false
- componentWillReceiveProps @19-19; FunctionExpression; parameters=1; async=false; generator=false
- getInitialState @19-19; FunctionExpression; parameters=0; async=false; generator=false
- r @19-19; FunctionDeclaration; parameters=0; async=false; generator=false
- n @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- render @19-19; FunctionExpression; parameters=0; async=false; generator=false
- componentWillMount @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=2; async=false; generator=false
- handleChange @19-19; FunctionExpression; parameters=1; async=false; generator=false
- componentDidUpdate @19-19; FunctionExpression; parameters=3; async=false; generator=false
- render @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getValue @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getChecked @19-19; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @19-19; FunctionExpression; parameters=0; async=false; generator=false
- getInitialState @19-19; FunctionExpression; parameters=0; async=false; generator=false
- manageChildrenByParentID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- dangerouslyReplaceNodeWithMarkupByID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- updateTextContentByID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- updateInnerHTMLByID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- updateStylesByID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- updatePropertiesByID @19-19; FunctionExpression; parameters=2; async=false; generator=false
- deletePropertyByID @19-19; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- u @20-20; FunctionExpression; parameters=5; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- checkArrayStrategy @20-20; FunctionExpression; parameters=1; async=false; generator=false
- checkMergeLevel @20-20; FunctionExpression; parameters=1; async=false; generator=false
- checkMergeObjectArg @20-20; FunctionExpression; parameters=1; async=false; generator=false
- checkMergeObjectArgs @20-20; FunctionExpression; parameters=2; async=false; generator=false
- checkMergeArrayArgs @20-20; FunctionExpression; parameters=2; async=false; generator=false
- normalizeMergeArg @20-20; FunctionExpression; parameters=1; async=false; generator=false
- a @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- r @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- o @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- o @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- r @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- r @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- o @20-20; FunctionExpression; parameters=1; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- thatReturnsArgument @20-20; FunctionExpression; parameters=1; async=false; generator=false
- thatReturnsThis @20-20; FunctionExpression; parameters=0; async=false; generator=false
- r @20-20; FunctionDeclaration; parameters=0; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=6; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- refreshScrollValues @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- closeAll @20-20; FunctionExpression; parameters=0; async=false; generator=false
- initializeAll @20-20; FunctionExpression; parameters=0; async=false; generator=false
- perform @20-20; FunctionExpression; parameters=8; async=false; generator=false
- isInTransaction @20-20; FunctionExpression; parameters=0; async=false; generator=false
- reinitializeTransaction @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- deltaY @20-20; FunctionExpression; parameters=1; async=false; generator=false
- deltaX @20-20; FunctionExpression; parameters=1; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- pageY @20-20; FunctionExpression; parameters=1; async=false; generator=false
- pageX @20-20; FunctionExpression; parameters=1; async=false; generator=false
- relatedTarget @20-20; FunctionExpression; parameters=1; async=false; generator=false
- button @20-20; FunctionExpression; parameters=1; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=2; async=false; generator=false
- n @20-20; FunctionDeclaration; parameters=3; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/bower_components/todomvc-common/base.js

Blob: `368e5ea03a61ad36679c15ea0af64891371db9ea`. Role: imported-path,source. Parse: module.

- (anonymous) @1-209; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-112; FunctionExpression; parameters=1; async=false; generator=false
- _.defaults @7-22; FunctionExpression; parameters=1; async=false; generator=false
- _.template @54-109; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @68-83; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @70-70; FunctionExpression; parameters=1; async=false; generator=false
- template @101-103; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @115-115; FunctionExpression; parameters=2; async=false; generator=false
- redirect @118-122; FunctionDeclaration; parameters=0; async=false; generator=false
- findRoot @124-136; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @127-133; FunctionExpression; parameters=1; async=false; generator=false
- getFile @138-153; FunctionDeclaration; parameters=2; async=false; generator=false
- xhr.onload @148-152; FunctionExpression; parameters=0; async=false; generator=false
- Learn @155-190; FunctionDeclaration; parameters=2; async=false; generator=false
- Learn.prototype.append @192-205; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @199-201; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/app.jsx

Blob: `1e1e2a3e127edcb4b71e3602087636df3ee19999`. Role: imported-path,source. Parse: module.

- (anonymous) @11-207; FunctionExpression; parameters=2; async=false; generator=false
- getInitialState @21-28; FunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @30-38; FunctionExpression; parameters=0; async=false; generator=false
- handleNewTodoKeyDown @40-61; FunctionExpression; parameters=1; async=false; generator=false
- toggleAll @63-71; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @66-68; FunctionExpression; parameters=1; async=false; generator=false
- toggle @73-76; FunctionExpression; parameters=1; async=false; generator=false
- destroy @78-84; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-81; FunctionExpression; parameters=1; async=false; generator=false
- edit @86-92; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @89-91; FunctionExpression; parameters=0; async=false; generator=false
- save @94-97; FunctionExpression; parameters=2; async=false; generator=false
- cancel @99-101; FunctionExpression; parameters=0; async=false; generator=false
- clearCompleted @103-109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @104-106; FunctionExpression; parameters=1; async=false; generator=false
- componentDidUpdate @111-113; FunctionExpression; parameters=0; async=false; generator=false
- render @115-194; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @122-131; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-145; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @147-149; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/footer.jsx

Blob: `5a896553da0b9ab41c98207742b9f3c358c5a3cd`. Role: imported-path,source. Parse: module.

- (anonymous) @9-58; FunctionExpression; parameters=1; async=false; generator=false
- render @13-56; FunctionExpression; parameters=0; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/todoItem.jsx

Blob: `87f6c1c6b3ce7579556f20a4b2f225a99c63c327`. Role: imported-path,source. Parse: module.

- (anonymous) @9-93; FunctionExpression; parameters=1; async=false; generator=false
- handleSubmit @16-25; FunctionExpression; parameters=0; async=false; generator=false
- handleEdit @26-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-35; FunctionExpression; parameters=0; async=false; generator=false
- handleKeyDown @38-47; FunctionExpression; parameters=1; async=false; generator=false
- handleChange @49-51; FunctionExpression; parameters=1; async=false; generator=false
- getInitialState @53-55; FunctionExpression; parameters=0; async=false; generator=false
- componentWillReceiveProps @57-61; FunctionExpression; parameters=1; async=false; generator=false
- render @63-91; FunctionExpression; parameters=0; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/labs/architecture-examples/react/js/utils.jsx

Blob: `3ce698563a2f10fafb413a9a557720837081f2d4`. Role: imported-path,source. Parse: module.

- (anonymous) @1-49; FunctionExpression; parameters=1; async=false; generator=false
- uuid @5-20; FunctionExpression; parameters=0; async=false; generator=false
- pluralize @22-24; FunctionExpression; parameters=2; async=false; generator=false
- store @26-33; FunctionExpression; parameters=2; async=false; generator=false
- stringifyObjKeys @35-46; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.app.930ad8b83126862d7445.js

Blob: `c93d24963afa979e3fd575e62e82a23ceac00e05`. Role: imported-path,source. Parse: module.

- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- value @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- value @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- value @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- value @1-1; FunctionExpression; parameters=2; async=false; generator=false
- editItemDone @1-1; FunctionExpression; parameters=0; async=false; generator=false
- editItem @1-1; FunctionExpression; parameters=0; async=false; generator=false
- elementComplete @1-1; FunctionExpression; parameters=0; async=false; generator=false
- clearNewTodo @1-1; FunctionExpression; parameters=0; async=false; generator=false
- setFilter @1-1; FunctionExpression; parameters=0; async=false; generator=false
- toggleAll @1-1; FunctionExpression; parameters=0; async=false; generator=false
- contentBlockVisibility @1-1; FunctionExpression; parameters=0; async=false; generator=false
- clearCompletedButton @1-1; FunctionExpression; parameters=0; async=false; generator=false
- updateElementCount @1-1; FunctionExpression; parameters=0; async=false; generator=false
- removeItem @1-1; FunctionExpression; parameters=0; async=false; generator=false
- showEntries @1-1; FunctionExpression; parameters=0; async=false; generator=false
- value @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- value @1-1; FunctionExpression; parameters=2; async=false; generator=false
- value @1-1; FunctionExpression; parameters=1; async=false; generator=false
- t @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- t @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- l @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- c @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- r @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- n @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- n @1-1; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o.prototype.clearCompletedButton @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.itemCounter @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.show @1-1; FunctionExpression; parameters=1; async=false; generator=false
- a @1-1; FunctionExpression; parameters=1; async=false; generator=false
- r @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o.prototype.drop @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.remove @1-1; FunctionExpression; parameters=2; async=false; generator=false
- o.prototype.save @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.findAll @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.find @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype._notify @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.subscribe @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o.prototype.getCount @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.removeAll @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.remove @1-1; FunctionExpression; parameters=2; async=false; generator=false
- o.prototype.update @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o.prototype.read @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.create @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- n.clear @1-1; FunctionExpression; parameters=0; async=false; generator=false
- n.key @1-1; FunctionExpression; parameters=1; async=false; generator=false
- n.removeItem @1-1; FunctionExpression; parameters=1; async=false; generator=false
- n.setItem @1-1; FunctionExpression; parameters=2; async=false; generator=false
- n.getItem @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o.prototype._updateFilterState @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype._filter @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype._updateCount @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.toggleAll @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.toggleComplete @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.removeCompletedItems @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.removeItem @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.editItemCancel @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.editItemSave @1-1; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.editItem @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.addItem @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- o.prototype.showCompleted @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.showActive @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.showAll @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o.prototype.setView @1-1; FunctionExpression; parameters=1; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- a @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- l @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- c @1-1; FunctionDeclaration; parameters=4; async=false; generator=false
- c @1-1; FunctionDeclaration; parameters=1; async=false; generator=false
- r @1-1; FunctionDeclaration; parameters=4; async=false; generator=false
- n @1-1; FunctionDeclaration; parameters=2; async=false; generator=false
- o @1-1; FunctionDeclaration; parameters=2; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.manifest.e81199b00da2921d9c94.js

Blob: `b456b9739f96f75d6c235018581202ec82757ccd`. Role: imported-path,source. Parse: module.

- (anonymous) @1-1; FunctionExpression; parameters=1; async=false; generator=false
- r.oe @1-1; FunctionExpression; parameters=1; async=false; generator=false
- r.o @1-1; FunctionExpression; parameters=2; async=false; generator=false
- r.n @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- r.d @1-1; FunctionExpression; parameters=3; async=false; generator=false
- r.i @1-1; FunctionExpression; parameters=1; async=false; generator=false
- r.e @1-1; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=2; async=false; generator=false
- n @1-1; FunctionDeclaration; parameters=0; async=false; generator=false
- window.webpackJsonp @1-1; FunctionExpression; parameters=3; async=false; generator=false
- r @1-1; FunctionDeclaration; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/dist/bundle.vendor.577c6bc09319b27fed34.js

Blob: `60cc6984ba7f8aafa53845ccc21afd05edcffce3`. Role: imported-path,source. Parse: module.

- (anonymous) @1-1; FunctionExpression; parameters=2; async=false; generator=false
- n.exports @1-1; FunctionExpression; parameters=0; async=false; generator=false
- n.i @1-1; FunctionExpression; parameters=2; async=false; generator=false
- n.toString @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1-1; FunctionExpression; parameters=2; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/app.js

Blob: `b7e02fde9023556c053a9b960820c9e3cfde60f7`. Role: imported-path,source. Parse: module.

- onLoad @7-9; FunctionDeclaration; parameters=0; async=false; generator=false
- Module todomvc-app-css/index.css @1; ImportDeclaration
- Module ./app.css @2; ImportDeclaration
- Module ./helpers @4; ImportDeclaration
- Module ./todo @5; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/bootstrap.js

Blob: `b6d5e821ba7ea6e9865f98c4cc5a50b5fd6e3091`. Role: imported-path,source. Parse: module.

- (anonymous) @9-10; FunctionExpression; parameters=1; async=false; generator=false
- bootstrap @20-23; FunctionDeclaration; parameters=0; async=false; generator=false
- Module ./app @2; ImportDeclaration
- Module ./helpers @3; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/controller.js

Blob: `8a48c906bc36ce4bc8b723f3f2ff0339440c5f43`. Role: imported-path,source. Parse: module.

- Controller @10-46; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @15-17; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-29; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.setView @53-57; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showAll @63-68; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @65-67; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showActive @73-78; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-77; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showCompleted @83-88; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @85-87; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.addItem @94-105; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @101-104; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.editItem @110-115; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @112-114; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.editItemSave @120-129; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @123-125; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.editItemCancel @134-139; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @136-138; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.removeItem @148-155; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @150-152; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.removeCompletedItems @160-169; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @162-166; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @163-165; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.toggleComplete @180-192; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @182-187; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.toggleAll @198-207; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @200-204; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @201-203; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._updateCount @213-225; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @215-224; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._filter @231-245; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._updateFilterState @250-263; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/controller.test.js

Blob: `b349559b9c837a7d58ea1a305cb77787abcd0f22`. Role: imported-path,source. Parse: module.

- (anonymous) @3-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ./controller @1; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/helpers.js

Blob: `e88ecb8d9446e51407b66bc0ba1a79d414bc8c65`. Role: imported-path,source. Parse: module.

- qs @4-6; FunctionDeclaration; parameters=2; async=false; generator=false
- qsa @8-10; FunctionDeclaration; parameters=2; async=false; generator=false
- $on @13-15; FunctionDeclaration; parameters=4; async=false; generator=false
- $delegate @19-33; FunctionDeclaration; parameters=4; async=false; generator=false
- dispatchEvent @24-32; FunctionDeclaration; parameters=1; async=false; generator=false
- $parent @37-45; FunctionDeclaration; parameters=2; async=false; generator=false
- remove @51-57; FunctionDeclaration; parameters=2; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/memory.js

Blob: `c81c0e511f9bfb23c0e5d0439a308b82fb84cd3c`. Role: imported-path,source. Parse: module.

- (anonymous) @1-82; FunctionExpression; parameters=1; async=false; generator=false
- localStorageMemory.getItem @17-19; FunctionExpression; parameters=1; async=false; generator=false
- localStorageMemory.setItem @30-40; FunctionExpression; parameters=2; async=false; generator=false
- localStorageMemory.removeItem @49-54; FunctionExpression; parameters=1; async=false; generator=false
- localStorageMemory.key @63-65; FunctionExpression; parameters=1; async=false; generator=false
- localStorageMemory.clear @72-75; FunctionExpression; parameters=0; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/model.js

Blob: `06fa58a6bed7323f62cf357251b9754382705f7c`. Role: imported-path,source. Parse: module.

- Model @9-11; FunctionDeclaration; parameters=1; async=false; generator=false
- Model.prototype.create @19-30; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-22; FunctionExpression; parameters=0; async=false; generator=false
- Model.prototype.read @46-61; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @48-49; FunctionExpression; parameters=0; async=false; generator=false
- Model.prototype.update @71-73; FunctionExpression; parameters=3; async=false; generator=false
- Model.prototype.remove @81-83; FunctionExpression; parameters=2; async=false; generator=false
- Model.prototype.removeAll @90-92; FunctionExpression; parameters=1; async=false; generator=false
- Model.prototype.getCount @97-116; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-115; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @105-113; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/store.js

Blob: `e3b64363607a5d98423ac318f0f34b483c493f2d`. Role: imported-path,source. Parse: module.

- Store @15-31; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @16-17; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.subscribe @33-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Store.prototype._notify @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Store.prototype.find @55-70; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @62-69; FunctionExpression; parameters=1; async=false; generator=false
- Store.prototype.findAll @77-81; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @78-79; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.save @91-120; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @95-96; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.remove @128-142; FunctionExpression; parameters=2; async=false; generator=false
- Store.prototype.drop @149-153; FunctionExpression; parameters=1; async=false; generator=false
- Module ./helpers @1; ImportDeclaration
- Module ./memory @2; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/template.js

Blob: `60c4f6fc84708f7cc38c6cca4dfbfb3dee9d4aef`. Role: imported-path,source. Parse: module.

- escapeHtmlChar @12-14; FunctionExpression; parameters=1; async=false; generator=false
- escape @19-25; FunctionExpression; parameters=1; async=false; generator=false
- Template @32-42; FunctionDeclaration; parameters=0; async=false; generator=false
- Template.prototype.show @61-84; FunctionExpression; parameters=1; async=false; generator=false
- Template.prototype.itemCounter @92-96; FunctionExpression; parameters=1; async=false; generator=false
- Template.prototype.clearCompletedButton @104-110; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/todo.js

Blob: `e51cf361aa35e234d2b267e8667eb0a87864bf66`. Role: imported-path,source. Parse: module.

- Todo @18-24; FunctionDeclaration; parameters=1; async=false; generator=false
- updateTodo @26-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getTodo @32-34; FunctionDeclaration; parameters=0; async=false; generator=false
- subscribe @36-41; FunctionDeclaration; parameters=1; async=false; generator=false
- unsubscribe @38-40; FunctionExpression; parameters=0; async=false; generator=false
- Module ./view @1; ImportDeclaration
- Module ./controller @2; ImportDeclaration
- Module ./model @3; ImportDeclaration
- Module ./store @4; ImportDeclaration
- Module ./template @5; ImportDeclaration
- Module ./helpers @6; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/src/view.js

Blob: `315ed5c5d25e6b0aa06f727f1a78a7d0ba10fe21`. Role: imported-path,source. Parse: module.

- constructor @14-27; FunctionExpression; parameters=1; async=false; generator=false
- _removeItem @29-35; FunctionExpression; parameters=1; async=false; generator=false
- _clearCompletedButton @37-40; FunctionExpression; parameters=2; async=false; generator=false
- _editItemDone @42-57; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @54-56; FunctionExpression; parameters=1; async=false; generator=false
- render @59-98; FunctionExpression; parameters=2; async=false; generator=false
- showEntries @62-64; FunctionExpression; parameters=0; async=false; generator=false
- removeItem @65-67; FunctionExpression; parameters=0; async=false; generator=false
- updateElementCount @68-70; FunctionExpression; parameters=0; async=false; generator=false
- clearCompletedButton @71-73; FunctionExpression; parameters=0; async=false; generator=false
- contentBlockVisibility @74-76; FunctionExpression; parameters=0; async=false; generator=false
- toggleAll @77-79; FunctionExpression; parameters=0; async=false; generator=false
- setFilter @80-82; FunctionExpression; parameters=0; async=false; generator=false
- clearNewTodo @83-85; FunctionExpression; parameters=0; async=false; generator=false
- elementComplete @86-88; FunctionExpression; parameters=0; async=false; generator=false
- editItem @89-91; FunctionExpression; parameters=0; async=false; generator=false
- editItemDone @92-94; FunctionExpression; parameters=0; async=false; generator=false
- _bindItemEditDone @100-118; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @102-109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-117; FunctionExpression; parameters=1; async=false; generator=false
- _bindItemEditCancel @120-130; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @122-129; FunctionExpression; parameters=1; async=false; generator=false
- bind @132-173; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @135-137; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @140-142; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @145-147; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @150-152; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @155-157; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @160-165; FunctionExpression; parameters=0; async=false; generator=false
- _setFilter @176-179; FunctionDeclaration; parameters=1; async=false; generator=false
- _elementComplete @181-192; FunctionDeclaration; parameters=2; async=false; generator=false
- _editItem @194-209; FunctionDeclaration; parameters=2; async=false; generator=false
- _itemId @211-214; FunctionDeclaration; parameters=1; async=false; generator=false
- Class View @13-174
- Module ./helpers @2; ImportDeclaration

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015-babel-webpack/webpack.config.babel.js

Blob: `4ec371be4e55b4487dc6e4f97cb999cfa0a63403`. Role: imported-path,source. Parse: module.

- module.exports @11-60; ArrowFunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/node_modules/todomvc-common/base.js

Blob: `e1676dbb8f7702b1e95fc578929ec2a2c149f254`. Role: imported-path,source. Parse: module.

- (anonymous) @2-249; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-114; FunctionExpression; parameters=1; async=false; generator=false
- _.defaults @9-24; FunctionExpression; parameters=1; async=false; generator=false
- _.template @56-111; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @70-85; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @72-72; FunctionExpression; parameters=1; async=false; generator=false
- template @103-105; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-120; FunctionExpression; parameters=7; async=false; generator=false
- (anonymous) @117-118; FunctionExpression; parameters=0; async=false; generator=false
- redirect @126-130; FunctionDeclaration; parameters=0; async=false; generator=false
- findRoot @132-135; FunctionDeclaration; parameters=0; async=false; generator=false
- getFile @137-152; FunctionDeclaration; parameters=2; async=false; generator=false
- xhr.onload @147-151; FunctionExpression; parameters=0; async=false; generator=false
- Learn @154-197; FunctionDeclaration; parameters=2; async=false; generator=false
- Learn.prototype.append @199-225; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @216-220; FunctionExpression; parameters=1; async=false; generator=false
- Learn.prototype.fetchIssueCount @227-245; FunctionExpression; parameters=0; async=false; generator=false
- xhr.onload @233-242; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/app.js

Blob: `e65d9c56d1b38a99b7ef17b8024cba207983e889`. Role: imported-path,source. Parse: module.

- setView @4-4; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @11-19; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class Todo @6-20

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/controller.js

Blob: `d2693ec20ee125bf81effe7a72b8374e1628d9a3`. Role: imported-path,source. Parse: module.

- constructor @9-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setView @27-31; FunctionExpression; parameters=1; async=false; generator=false
- showAll @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- showActive @43-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- showCompleted @50-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addItem @58-67; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- editItem @72-77; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @73-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- editItemSave @82-92; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @86-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- editItemCancel @97-102; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @98-101; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeItem @108-111; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @109-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeCompletedItems @116-124; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-121; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggleComplete @135-143; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @136-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleAll @149-157; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @150-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _updateCount @163-175; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @164-174; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _filter @181-196; FunctionExpression; parameters=1; async=false; generator=false
- _updateFilter @201-213; FunctionExpression; parameters=1; async=false; generator=false
- Class Controller @3-214

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/helpers.js

Blob: `154fc483515f819c5443398b429fe4c25db57ec8`. Role: imported-path,source. Parse: module.

- qs @9-11; FunctionDeclaration; parameters=2; async=false; generator=false
- qsa @13-15; FunctionDeclaration; parameters=2; async=false; generator=false
- $on @18-20; FunctionDeclaration; parameters=4; async=false; generator=false
- $delegate @24-39; FunctionDeclaration; parameters=4; async=false; generator=false
- dispatchEvent @25-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- $parent @43-53; FunctionDeclaration; parameters=2; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/model.js

Blob: `cf8d58181bb52133f0cf67cdbe6376cf6a7ea787`. Role: imported-path,source. Parse: module.

- constructor @10-12; FunctionExpression; parameters=1; async=false; generator=false
- create @20-29; FunctionExpression; parameters=2; async=false; generator=false
- read @46-58; FunctionExpression; parameters=2; async=false; generator=false
- update @68-70; FunctionExpression; parameters=3; async=false; generator=false
- remove @78-80; FunctionExpression; parameters=2; async=false; generator=false
- removeAll @87-89; FunctionExpression; parameters=1; async=false; generator=false
- getCount @94-116; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @101-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Model @9-117

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/store.js

Blob: `dc22f251073d028dc2ef9048e08a137dcabdf0ed`. Role: imported-path,source. Parse: module.

- constructor @15-30; FunctionExpression; parameters=2; async=false; generator=false
- find @45-60; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @52-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findAll @67-71; FunctionExpression; parameters=1; async=false; generator=false
- save @81-113; FunctionExpression; parameters=3; async=false; generator=false
- remove @121-138; FunctionExpression; parameters=2; async=false; generator=false
- drop @145-151; FunctionExpression; parameters=1; async=false; generator=false
- Class Store @14-152

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/template.js

Blob: `77d4dd4c60be2653881a280e8da7df8d3d631306`. Role: imported-path,source. Parse: module.

- escape @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- escapeHtmlChar @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @20-30; FunctionExpression; parameters=0; async=false; generator=false
- show @49-73; FunctionExpression; parameters=1; async=false; generator=false
- itemCounter @81-84; FunctionExpression; parameters=1; async=false; generator=false
- clearCompletedButton @92-94; FunctionExpression; parameters=1; async=false; generator=false
- Class Template @19-95

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/es2015/src/view.js

Blob: `4ba35d219c2a520bb16eed98209b1875b7ff79e6`. Role: imported-path,source. Parse: module.

- _itemId @6-6; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _setFilter @8-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _elementComplete @13-24; ArrowFunctionExpression; parameters=2; async=false; generator=false
- _editItem @26-41; ArrowFunctionExpression; parameters=2; async=false; generator=false
- constructor @53-80; FunctionExpression; parameters=1; async=false; generator=false
- showEntries @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeItem @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateElementCount @70-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clearCompletedButton @71-71; ArrowFunctionExpression; parameters=1; async=false; generator=false
- contentBlockVisibility @72-72; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggleAll @73-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setFilter @74-74; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clearNewTodo @75-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- elementComplete @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- editItem @77-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- editItemDone @78-78; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _removeItem @82-88; FunctionExpression; parameters=1; async=false; generator=false
- _clearCompletedButton @90-93; FunctionExpression; parameters=2; async=false; generator=false
- _editItemDone @95-108; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- render @110-112; FunctionExpression; parameters=2; async=false; generator=false
- _bindItemEditDone @114-132; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-124; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-131; FunctionExpression; parameters=1; async=false; generator=false
- _bindItemEditCancel @134-146; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @137-145; FunctionExpression; parameters=1; async=false; generator=false
- bind @148-177; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @150-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @154-156; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @158-160; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @162-164; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @166-171; FunctionExpression; parameters=0; async=false; generator=false
- Class View @52-178

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/app.js

Blob: `301cf9feae48552e67d8078ae9fa37174d4c38d4`. Role: imported-path,source. Parse: module.

- (anonymous) @2-25; FunctionExpression; parameters=0; async=false; generator=false
- Todo @10-16; FunctionDeclaration; parameters=1; async=false; generator=false
- setView @20-22; FunctionDeclaration; parameters=0; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/controller.js

Blob: `0fbc62a89e65eb7b81407bcbd17cfb027b4ce687`. Role: imported-path,source. Parse: module.

- (anonymous) @1-270; FunctionExpression; parameters=1; async=false; generator=false
- Controller @11-47; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-22; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.setView @54-58; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showAll @64-69; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-68; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showActive @74-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-78; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.showCompleted @84-89; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-88; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.addItem @95-106; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @102-105; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.editItem @111-116; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @113-115; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.editItemSave @121-132; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @126-128; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.editItemCancel @137-142; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @139-141; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.removeItem @151-158; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @153-155; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.removeCompletedItems @163-172; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-169; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @166-168; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype.toggleComplete @183-195; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @185-190; FunctionExpression; parameters=0; async=false; generator=false
- Controller.prototype.toggleAll @201-210; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @203-207; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @204-206; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._updateCount @216-228; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @218-227; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._filter @234-248; FunctionExpression; parameters=1; async=false; generator=false
- Controller.prototype._updateFilterState @253-265; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/helpers.js

Blob: `2af956f064d8818dfc5f1591dc667c1ba86fd10c`. Role: imported-path,source. Parse: module.

- (anonymous) @2-52; FunctionExpression; parameters=1; async=false; generator=false
- window.qs @6-8; FunctionExpression; parameters=2; async=false; generator=false
- window.qsa @9-11; FunctionExpression; parameters=2; async=false; generator=false
- window.$on @14-16; FunctionExpression; parameters=4; async=false; generator=false
- window.$delegate @20-35; FunctionExpression; parameters=4; async=false; generator=false
- dispatchEvent @21-29; FunctionDeclaration; parameters=1; async=false; generator=false
- window.$parent @39-47; FunctionExpression; parameters=2; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/model.js

Blob: `d8a73191d2c2df5b23723aaa41339db8dba79b4f`. Role: imported-path,source. Parse: module.

- (anonymous) @1-120; FunctionExpression; parameters=1; async=false; generator=false
- Model @10-12; FunctionDeclaration; parameters=1; async=false; generator=false
- Model.prototype.create @20-30; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false
- Model.prototype.read @47-60; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @49-49; FunctionExpression; parameters=0; async=false; generator=false
- Model.prototype.update @70-72; FunctionExpression; parameters=3; async=false; generator=false
- Model.prototype.remove @80-82; FunctionExpression; parameters=2; async=false; generator=false
- Model.prototype.removeAll @89-91; FunctionExpression; parameters=1; async=false; generator=false
- Model.prototype.getCount @96-115; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @103-114; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-112; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/store.js

Blob: `7b28ccdfa72a8aeeec2a5b33ba0a1af1f0a9f93b`. Role: imported-path,source. Parse: module.

- (anonymous) @2-144; FunctionExpression; parameters=1; async=false; generator=false
- Store @16-30; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.find @45-60; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @52-59; FunctionExpression; parameters=1; async=false; generator=false
- Store.prototype.findAll @67-70; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-68; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.save @80-107; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @84-84; FunctionExpression; parameters=0; async=false; generator=false
- Store.prototype.remove @115-128; FunctionExpression; parameters=2; async=false; generator=false
- Store.prototype.drop @135-139; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/template.js

Blob: `43724c652952b557bb621ca0ba0dba05fd5f9800`. Role: imported-path,source. Parse: module.

- (anonymous) @2-114; FunctionExpression; parameters=1; async=false; generator=false
- escapeHtmlChar @14-16; FunctionExpression; parameters=1; async=false; generator=false
- escape @21-25; FunctionExpression; parameters=1; async=false; generator=false
- Template @32-41; FunctionDeclaration; parameters=0; async=false; generator=false
- Template.prototype.show @60-83; FunctionExpression; parameters=1; async=false; generator=false
- Template.prototype.itemCounter @91-95; FunctionExpression; parameters=1; async=false; generator=false
- Template.prototype.clearCompletedButton @103-109; FunctionExpression; parameters=1; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/js/view.js

Blob: `68de8305136d18c90bd60a67dbb5f5435a7112db`. Role: imported-path,source. Parse: module.

- (anonymous) @3-219; FunctionExpression; parameters=1; async=false; generator=false
- View @15-28; FunctionDeclaration; parameters=1; async=false; generator=false
- View.prototype._removeItem @30-36; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype._clearCompletedButton @38-41; FunctionExpression; parameters=2; async=false; generator=false
- View.prototype._setFilter @43-46; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype._elementComplete @48-59; FunctionExpression; parameters=2; async=false; generator=false
- View.prototype._editItem @61-76; FunctionExpression; parameters=2; async=false; generator=false
- View.prototype._editItemDone @78-93; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @90-92; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype.render @95-134; FunctionExpression; parameters=2; async=false; generator=false
- showEntries @98-100; FunctionExpression; parameters=0; async=false; generator=false
- removeItem @101-103; FunctionExpression; parameters=0; async=false; generator=false
- updateElementCount @104-106; FunctionExpression; parameters=0; async=false; generator=false
- clearCompletedButton @107-109; FunctionExpression; parameters=0; async=false; generator=false
- contentBlockVisibility @110-112; FunctionExpression; parameters=0; async=false; generator=false
- toggleAll @113-115; FunctionExpression; parameters=0; async=false; generator=false
- setFilter @116-118; FunctionExpression; parameters=0; async=false; generator=false
- clearNewTodo @119-121; FunctionExpression; parameters=0; async=false; generator=false
- elementComplete @122-124; FunctionExpression; parameters=0; async=false; generator=false
- editItem @125-127; FunctionExpression; parameters=0; async=false; generator=false
- editItemDone @128-130; FunctionExpression; parameters=0; async=false; generator=false
- View.prototype._itemId @136-139; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype._bindItemEditDone @141-159; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @143-150; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-158; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype._bindItemEditCancel @161-171; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @163-170; FunctionExpression; parameters=1; async=false; generator=false
- View.prototype.bind @173-214; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @176-178; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @181-183; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @186-188; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @191-193; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @196-198; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @201-206; FunctionExpression; parameters=0; async=false; generator=false

### third_party/webkit/PerformanceTests/Speedometer/resources/todomvc/vanilla-examples/vanillajs/node_modules/todomvc-common/base.js

Blob: `e1676dbb8f7702b1e95fc578929ec2a2c149f254`. Role: imported-path,source. Parse: module.

- (anonymous) @2-249; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-114; FunctionExpression; parameters=1; async=false; generator=false
- _.defaults @9-24; FunctionExpression; parameters=1; async=false; generator=false
- _.template @56-111; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @70-85; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @72-72; FunctionExpression; parameters=1; async=false; generator=false
- template @103-105; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-120; FunctionExpression; parameters=7; async=false; generator=false
- (anonymous) @117-118; FunctionExpression; parameters=0; async=false; generator=false
- redirect @126-130; FunctionDeclaration; parameters=0; async=false; generator=false
- findRoot @132-135; FunctionDeclaration; parameters=0; async=false; generator=false
- getFile @137-152; FunctionDeclaration; parameters=2; async=false; generator=false
- xhr.onload @147-151; FunctionExpression; parameters=0; async=false; generator=false
- Learn @154-197; FunctionDeclaration; parameters=2; async=false; generator=false
- Learn.prototype.append @199-225; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @216-220; FunctionExpression; parameters=1; async=false; generator=false
- Learn.prototype.fetchIssueCount @227-245; FunctionExpression; parameters=0; async=false; generator=false
- xhr.onload @233-242; FunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
