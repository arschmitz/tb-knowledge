<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T18:29:26.555426+00:00","paths":["js/src/wasm/WasmComponent.cpp","js/src/wasm/WasmValidate.cpp","js/src/wasm/WasmComponent.h","js/src/wasm/WasmProcess.cpp","js/src/jit-test/tests/wasm/components/strongly-unique.js","js/src/jit-test/tests/wasm/components/directives.txt"],"source":{"reference":"https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp","status":"provisional","pairedRevisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","git:314d8065c5ad68c7e5c5f92d":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"publicationKey":"capacity-calibration-20261013-ff-cpp-large-challenge","analysisDecision":"accepted-partial","sourceHash":"4264feba5b4edf3fd50a7d91cd89b19bca0349e4db08649159a5a1ea52dbb0c9","analysisHash":"360828b074459b7fdd01fa49e2278093be8260a020531e61dc8873c4ecee3326"}} -->
# WasmComponent.cpp: implementation, consumers and test limits

Source: `git:314d8065c5ad68c7e5c5f92d` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Path: `js/src/wasm/WasmComponent.cpp`. Language: C++. Role: production. Component: `js`. Runtime details appear in the scoped contracts below; unspecified runtime fields remain unresolved.

Independent AI source review: **accepted-partial**. This records source reading and checked immediate relationships. It is not a runtime test result or a claim that every transitive dependency is fully understood. Suite is excluded. These observations do not change project instructions.

## Scope and open work

- Required: The1952-line target was not fully analyzed. Type constructors/accessors, structural equality, complete hashing, caller/test linkage for flattening rules, import/export metadata, resolution, dummy lowered-function generation, full init and string conversion bodies remain.
- Required: Saved C++ parser status contains-errors and mislabels numerous bodies ENABLE_WASM_COMPONENTS. Function/nested-lambda census must be repaired before all-body completion can be asserted.
- Required: Native reference counting, garbage collection, the complete instance-creation/error cleanup chain, feature configuration and all relevant test assertions remain open.
- Required: Strongly-unique test helper execution/assertion path remains unverified.
- Limit: Partial whole-file benchmark; no completed-file throughput credit.
- Limit: No product test run.
- Limit: Selected local bodies and callers are useful reusable evidence; this is not full component-model understanding.
- Limit: Reviewed selected 24 units and actual quoted caller/name/shutdown links, not all 1952 lines.
- Limit: All 31 current exact evidence quotations match pinned source.
- Limit: Useful selected body evidence is partial; no completed-file throughput credit.
- Limit: Did not certify dynamic ownership/cleanup or strongly-unique test helper. No tests executed.
- Limit: Metadata corrections are accepted; whole 1952-line source and required wider ownership/validation/test routes are still incomplete.
- Limit: Initial review did not read the full target. This record gives no completed-file throughput credit.
- Limit: No tests executed.

## Implementation sections

### feature gates and imports (7–31)

Compile component-model code only under ENABLE_WASM_COMPONENTS. Debug name character checking has a separate DEBUG gate.

- Reads: None recorded.
- Changes: None recorded.
- Conditions: ENABLE_WASM_COMPONENTS; DEBUG
- Result: Compile-time selection.
- Errors: Compile-time inclusion only; this section returns no runtime status and performs no assertion.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Compile-time names and gates; no runtime object created by this section.

- [js/src/wasm/WasmComponent.cpp:7–31](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L7-L31), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
#include "wasm/WasmComponent.h"

#include "wasm/WasmBinary.h"
```


### NameIsProbablyValid (32–42)

Returns false on the first character outside ASCII letters/digits, hyphen, dot and brackets; returns true if all characters pass, including an empty span.

- Reads: name characters
- Changes: None recorded.
- Conditions: None recorded.
- Result: Boolean character check. This is not full name grammar validation.
- Errors: Returns false for an unsupported character. Its own body has no assertion, allocation, or exception handling.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:32–42](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L32-L42), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
static bool NameIsProbablyValid(mozilla::Span<const char> name) {
  for (char c : name) {
    bool validChar = ('a' <= c && c <= 'z') || ('A' <= c && c <= 'Z') ||
```


### CanonicalizeName (45–109)

Reserves input-sized storage. Lowercases ASCII capitals and removes hyphens. Tracks the final closing bracket and final dot. If text between that bracket and dot equals text after the dot, moves that text to the beginning and returns it. Otherwise strips initial method/static and then get attributes while retaining constructor/set. Moves the resulting bytes into the output.

- Reads: name span
- Changes: temporary UTF8Bytes; *result
- Conditions: reserve failure; uppercase/hyphen/other byte; dot and repeated-name simplification; leading attribute trimming
- Result: True on local success; false on allocation failure.
- Errors: Returns false if buffer reserve fails. Debug assertions require accepted characters and a valid attribute/dot ordering. Broader name-grammar and empty-input preconditions remain a caller gap.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Moves owned normalized bytes into CacheableName; input span remains borrowed.

- [js/src/wasm/WasmComponent.cpp:45–109](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L45-L109), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool wasm::CanonicalizeName(mozilla::Span<const char> name,
                            CacheableName* result) {
  MOZ_ASSERT(NameIsProbablyValid(name));
```


### ComponentName::getterForSetter (111–142)

Requires a Set attribute, rebuilds existing constructor/method/static attributes, appends get instead of set, then copies the name suffix past attributesLength. Returns the UTF8-to-CacheableName conversion result.

- Reads: attributes; attributesLength; name
- Changes: temporary bytes; out
- Conditions: Each present attribute; Each append may fail
- Result: False on an append failure; otherwise returns fromUTF8Bytes status.
- Errors: Release-asserts the Set attribute, returns false on an append failure, then forwards fromUTF8Bytes status. Other failure causes in fromUTF8Bytes were not checked.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Builds new owned name; original name remains unchanged.

- [js/src/wasm/WasmComponent.cpp:111–142](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L111-L142), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool ComponentName::getterForSetter(CacheableName* out) const {
  MOZ_RELEASE_ASSERT(attributes.contains(ComponentNameAttribute::Set));

```


### StronglyUniqueNameSet::add (144–159)

Sets duplicate false first, canonicalizes a copy of the supplied name, and looks up that normalized byte sequence. A found key sets duplicate true and returns success; a missing key moves the new name into the set.

- Reads: name; data_
- Changes: *duplicate; data_ when new
- Conditions: Canonicalization failure; Duplicate success; Insertion success/failure
- Result: False on failed canonicalization or insertion; true with duplicate=true for an existing key.
- Errors: Returns false when CanonicalizeName fails, otherwise returns insertion status for a new key. A duplicate is successful with duplicate=true.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Set owns inserted normalized names; a duplicate temporary is discarded.

- [js/src/wasm/WasmComponent.cpp:144–159](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L144-L159), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool StronglyUniqueNameSet::add(mozilla::Span<const char> name,
                                bool* duplicate) {
  *duplicate = false;
```


### Builder::trackItemOfSort (161–190)

Selects the counter for the component/core sort, returns its previous value and increments it. Unknown sorts crash.

- Reads: sort; per-sort counters
- Changes: One matching counter
- Conditions: Func,Type,Component,Instance; CoreFunction,CoreTable,CoreMemory,CoreGlobal,CoreTag,CoreType,CoreModule,CoreInstance; default crash
- Result: Index within the chosen sort.
- Errors: MOZ_CRASH for a sort not handled by the switch. The body has no false return.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:161–190](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L161-L190), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
uint32_t ComponentInlineExports::Builder::trackItemOfSort(ComponentSort sort) {
  switch (sort) {
    case ComponentSort::Func:
```


### ComponentInlineExports::addExport (192–212)

Reserves a sort-specific instance index by incrementing the builder, inserts name to local sort/index, then local sort/index to original export index. Duplicate lookups release-assert. Failure of either insertion returns false; earlier counter/map changes are not rolled back locally.

- Reads: exported.sort/index; builder
- Changes: builder counter; exports_; originalIndices_
- Conditions: First insertion failure; Second insertion failure
- Result: False on either map insertion failure; true after both insertions.
- Errors: Release-asserts that both map lookups are absent. Returns false on either map insertion failure, without undoing preceding local mutations.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Moves name into exports_ on first insertion; caller failure handling remains unreviewed.

- [js/src/wasm/WasmComponent.cpp:192–212](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L192-L212), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool ComponentInlineExports::addExport(Builder* builder, CacheableName&& name,
                                       ComponentSortIndex exported) {
  uint32_t indexInThisInstance = builder->trackItemOfSort(exported.sort);
```


### ComponentInlineExports::getExport (214–221)

Looks up the name bytes in exports_; returns Nothing if absent and Some stored sort/index if found.

- Reads: exports_; name
- Changes: None recorded.
- Conditions: None recorded.
- Result: Maybe<ComponentSortIndex>.
- Errors: Returns Nothing for an absent key. No assertion or false return occurs in this body; external lookup failure behavior was not expanded.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:214–221](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L214-L221), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
mozilla::Maybe<ComponentSortIndex> ComponentInlineExports::getExport(
    const CacheableName& name) const {
  auto p = exports_.lookup(name.utf8Bytes());
```


### ComponentInlineExports::resolveOriginal (223–230)

Requires a local sort/index mapping to exist. Returns an original index with the same sort.

- Reads: originalIndices_; expFromThis
- Changes: None recorded.
- Conditions: None recorded.
- Result: ComponentSortIndex with original index.
- Errors: Release-asserts that the original-index lookup exists. Debug-asserts sort preservation.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:223–230](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L223-L230), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
ComponentSortIndex ComponentInlineExports::resolveOriginal(
    ComponentSortIndex expFromThis) const {
  auto p = originalIndices_.lookup(expFromThis);
```


### ComponentInlineExports::mustResolveExportToOriginal (232–236)

Requires getExport to contain a value and passes that local index to resolveOriginal.

- Reads: name; exports_; originalIndices_
- Changes: None recorded.
- Conditions: None recorded.
- Result: Original sort/index; no absent-name recovery.
- Errors: Dereferences the Maybe from getExport without an absence branch, then forwards resolveOriginal. Exact Maybe::value failure behavior was not expanded.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:232–236](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L232-L236), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
ComponentSortIndex ComponentInlineExports::mustResolveExportToOriginal(
    const CacheableName& name) const {
  ComponentSortIndex expInThis = getExport(name).value();
```


### ComponentCanonicalTypeSet::canonicalize (796–829)

Requires a valid type. Returns primitives directly without storing them and preserves resource/subresource uniqueness by bypassing deduplication. Other kinds use canonicalTypes_ lookup; reuse a found type or insert the new type. Assignment to output occurs only on success.

- Reads: type kind/definition; canonicalTypes_
- Changes: canonicalTypes_ on new type; *canonicalized
- Conditions: Primitive; Resource/SubResource; Existing structural key; Insertion failure
- Result: False on a new-set insertion failure; true after assigning the existing or newly canonicalized type.
- Errors: Release-asserts a valid type and expected definition presence. Returns false when the new canonical-set insertion fails.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Set retains inserted ComponentType references. Hash/match and type reference-counting contracts need deeper review.

- [js/src/wasm/WasmComponent.cpp:796–829](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L796-L829), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool ComponentCanonicalTypeSet::canonicalize(const ComponentType& type,
                                             ComponentType* canonicalized) {
  MOZ_RELEASE_ASSERT(type.isValid());
```


### global canonical set and CanonicalizeComponentType (831–839)

Creates an ExclusiveData wrapper with the named component-type mutex. The function obtains its guard and forwards canonicalization while the guard is alive.

- Reads: sComponentCanonicalTypeSet
- Changes: Shared canonical set via guarded call
- Conditions: None recorded.
- Result: Canonicalization result.
- Errors: Returns the guarded canonicalize status. Lock acquisition and release failures were not investigated.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local guard bounds access; exact mutex/reference semantics not expanded.

- [js/src/wasm/WasmComponent.cpp:831–839](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L831-L839), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
MOZ_RUNINIT static ExclusiveData<ComponentCanonicalTypeSet>
    sComponentCanonicalTypeSet(mutexid::WasmComponentCanonicalTypeSet);

```


### PurgeComponentCanonicalTypes (841–845)

Locks the shared set and clears/compacts all retained canonical types.

- Reads: sComponentCanonicalTypeSet
- Changes: canonicalTypes_ cleared
- Conditions: None recorded.
- Result: Void.
- Errors: Void function with no local error return or assertion. External lock and clearAndCompact failure behavior remains unchecked.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Releases set entries through container clear; type destructor details not checked.

- [js/src/wasm/WasmComponent.cpp:841–845](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L841-L845), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
void wasm::PurgeComponentCanonicalTypes() {
  ExclusiveData<ComponentCanonicalTypeSet>::Guard locked =
      sComponentCanonicalTypeSet.lock();
```


### Component::instantiate (1564–1573)

Creates the JavaScript component-instance object, assigns the output handle, returns false if absent and true if present.

- Reads: cx; instanceProto; this component
- Changes: instance output handle
- Conditions: None recorded.
- Result: True when create returns a non-null object; false when it returns null. The causes of null are unresolved.
- Errors: Returns false when WasmComponentInstanceObject::create returns null. Creation failure causes and exception state remain unresolved because that callee was not read.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Actual JavaScript object creation/cleanup lies in an unread callee.

- [js/src/wasm/WasmComponent.cpp:1564–1573](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1564-L1573), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool Component::instantiate(
    JSContext* cx, HandleObject instanceProto,
    MutableHandle<WasmComponentInstanceObject*> instance) const {
```


### ComponentInstance constructor/destructor (1575–1580)

Stores current realm, JSContext and a shared component. The destructor is defaulted.

- Reads: cx; component
- Changes: realm_; cx_; component_
- Conditions: None recorded.
- Result: Native instance.
- Errors: No explicit local failure handling or assertion. Member construction, reference management, and defaulted destruction contracts remain unchecked.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Shared component retained by member; member cleanup details remain open.

- [js/src/wasm/WasmComponent.cpp:1575–1580](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1575-L1580), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
ComponentInstance::ComponentInstance(
    JSContext* cx, Handle<WasmComponentInstanceObject*> object,
    const SharedComponent component)
```


### ComponentInstance::create (1582–1592)

Allocates the native instance with js_new. On null reports out-of-memory and returns null; otherwise returns the pointer.

- Reads: cx; object; component
- Changes: None recorded.
- Conditions: None recorded.
- Result: New native pointer or null.
- Errors: If js_new returns null, calls ReportOutOfMemory and returns null. Deeper allocation/constructor failure semantics were not expanded.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Returned allocation must later pass to destroy.

- [js/src/wasm/WasmComponent.cpp:1582–1592](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1582-L1592), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
ComponentInstance* ComponentInstance::create(
    JSContext* cx, Handle<WasmComponentInstanceObject*> object,
    const SharedComponent component) {
```


### ComponentInstance::destroy (1594–1597)

Explicitly runs the destructor then frees the native allocation.

- Reads: instance
- Changes: Instance allocation released
- Conditions: None recorded.
- Result: Void.
- Errors: Void function with no null guard or local status. Destructor and allocator failure behavior were not expanded.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Consumes the native pointer; no null check.

- [js/src/wasm/WasmComponent.cpp:1594–1597](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1594-L1597), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
void ComponentInstance::destroy(ComponentInstance* instance) {
  instance->~ComponentInstance();
  js_free(instance);
```


### ComponentInstance::tracePrivate (1599–1601)

Traces coreInstances_ with the supplied garbage-collection tracer.

- Reads: coreInstances_
- Changes: None recorded.
- Conditions: None recorded.
- Result: Void.
- Errors: Void function forwarding to coreInstances_.trace. External tracing failure semantics were not expanded.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Reports retained core instances to tracing; broader rooting lifecycle remains open.

- [js/src/wasm/WasmComponent.cpp:1599–1601](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1599-L1601), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
void ComponentInstance::tracePrivate(JSTracer* trc) {
  coreInstances_.trace(trc);
}
```


### GetValidatedNamedPropertyFromObject (1605–1615)

Atomizes the cached name, returning false on failure. Converts the atom to a rooted property ID and gets the property, release-asserting success because validation must have made this infallible.

- Reads: obj; name
- Changes: exportVal
- Conditions: Atomization failure; GetProperty release assertion
- Result: Boolean completion.
- Errors: Returns false when toAtom returns null. Release-asserts successful JS_GetPropertyById; details of atomization failure remain an external contract gap.
- Async completion: This selected body is synchronous; no promise/cancellation mechanism.
- Ownership and release: Local ownership only; broader owner requires the remaining file review.

- [js/src/wasm/WasmComponent.cpp:1605–1615](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1605-L1615), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
[[nodiscard]] static bool GetValidatedNamedPropertyFromObject(
    JSContext* cx, HandleObject obj, const CacheableName& name,
    MutableHandleValue exportVal) {
```


### FlattenFuncType (847–929)

Flattens parameters and optional result. String/list parameters need realloc when lifting and memory when lowering; results reverse those requirements. More than16flat parameters become one i32memory pointer. More than1flat result becomes one i32result pointer for lift, or an appended i32out-parameter with no return value for lower. Realloc always implies memory. Returns Nothing on any nested/append failure and Some moved FuncType on success. Output flags are only set true, so caller initialization matters.

- Reads: funcType.paramTypes; optional funcType.resultType; mode; incoming reallocRequired flag
- Changes: local params and results vectors; memoryRequired flag; reallocRequired flag; tooDeep flag through nested flattening
- Conditions: All explicit type/mode/size/error branches described above.
- Result: Nothing on failure; Some(FuncType) owning the moved parameter and result vectors on success.
- Errors: Returns Nothing when nested flattening or local append fails. Nested failure may mean excessive depth or allocation failure. Output flags can already be changed at failure.
- Async completion: Synchronous recursive flattening; no cancellation token.
- Ownership and release: Local vectors own temporary storage; successful function type moves vectors into its result. No listener or external asynchronous operation.

- [js/src/wasm/WasmComponent.cpp:847–929](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L847-L929), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
mozilla::Maybe<FuncType> wasm::FlattenFuncType(
    const ComponentFuncType& funcType, CanonMode mode, bool* memoryRequired,
    bool* reallocRequired, bool* tooDeep) {
```


### FlattenTypes (931–948)

Reserves at least the number of input types, then visits them in order and appends their flattened forms. Reserve or nested failure returns false. Partial appended output remains for the caller to discard.

- Reads: types; depth; existing result vector and output flags
- Changes: result vector; hasStringsOrLists flag through flattening; tooDeep flag through flattening
- Conditions: All explicit type/mode/size/error branches described above.
- Result: Boolean success; result and flags may be partly updated when false is returned.
- Errors: Returns false when reserve or nested FlattenType fails. Nested failure may mean excessive depth or allocation failure; output can remain partially appended.
- Async completion: Synchronous recursive flattening; no cancellation token.
- Ownership and release: Borrows input types and output pointers. The caller owns the result vector; temporary nested vectors are local where present.

- [js/src/wasm/WasmComponent.cpp:931–948](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L931-L948), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool wasm::FlattenTypes(const ComponentTypeVector& types, ValTypeVector* result,
                        bool* hasStringsOrLists, bool* tooDeep,
                        uint32_t depth) {
```


### JoinVariantValType (950–960)

Requires numeric types. Equal types remain equal; mixed i32/f32 joins to i32; all other unequal numeric pairs join to i64.

- Reads: a; b
- Changes: None recorded.
- Conditions: All explicit type/mode/size/error branches described above.
- Result: A ValType value: unchanged equal type, i32 for mixed i32/f32, otherwise i64.
- Errors: Debug-asserts numeric inputs. Returns a ValType; no allocation, false/Nothing return, or output mutation occurs in this body.
- Async completion: Synchronous recursive flattening; no cancellation token.
- Ownership and release: Input and output ValType values are passed by value; no owned vector or borrowed output pointer.

- [js/src/wasm/WasmComponent.cpp:950–960](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L950-L960), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
static ValType JoinVariantValType(ValType a, ValType b) {
  MOZ_ASSERT(a.isNumber() && b.isNumber());
  if (a == b) {
```


### FlattenType (962–1127)

Rejects depth above MaxComponentFlatteningDepth and sets tooDeep. Increments depth for nested calls. Bool/small integers/char/flags/enum/own/borrow append i32;64-bit integers append i64; floats preserve width. String/list set hasStringsOrLists and append2i32values. Record/tuple flatten fields/elements recursively. Variant prepends i32discriminant then overlaps case payload slots with numeric joins. Option prepends i32and its inner payload. Result prepends i32and overlaps optional success/error payloads. Append/nested failure preserves partial output and returns false; invalid type kind crashes.

- Reads: type and nested fields; depth; existing result vector and output flags
- Changes: result vector; hasStringsOrLists flag through flattening; tooDeep flag through flattening
- Conditions: All explicit type/mode/size/error branches described above.
- Result: Boolean success; result and flags may be partly updated when false is returned.
- Errors: Sets tooDeep and returns false above MaxComponentFlatteningDepth. Append or recursive failure returns false with partial output retained. Unhandled component kinds crash.
- Async completion: Synchronous recursive flattening; no cancellation token.
- Ownership and release: Borrows input types and output pointers. The caller owns the result vector; temporary nested vectors are local where present.

- [js/src/wasm/WasmComponent.cpp:962–1127](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L962-L1127), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool wasm::FlattenType(const ComponentType& type, ValTypeVector* result,
                       bool* hasStringsOrLists, bool* tooDeep, uint32_t depth) {
  if (depth > MaxComponentFlatteningDepth) {
```


### FlattenRecord (1129–1139)

Visits record fields in order and appends each field type through FlattenType. Stops at first failure; returns true after all fields.

- Reads: fields and each field.type; depth; existing result vector and output flags
- Changes: result vector; hasStringsOrLists flag through flattening; tooDeep flag through flattening
- Conditions: All explicit type/mode/size/error branches described above.
- Result: Boolean success; result and flags may be partly updated when false is returned.
- Errors: Returns false at the first nested FlattenType failure, preserving earlier appended fields. Otherwise returns true. No local allocation or assertion is authored outside nested calls.
- Async completion: Synchronous recursive flattening; no cancellation token.
- Ownership and release: Borrows input types and output pointers. The caller owns the result vector; temporary nested vectors are local where present.

- [js/src/wasm/WasmComponent.cpp:1129–1139](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.cpp#L1129-L1139), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
bool wasm::FlattenRecord(const ComponentRecordFieldVector& fields,
                         ValTypeVector* result, bool* hasStringsOrLists,
                         bool* tooDeep, uint32_t depth) {
```


## Relationships

### 1. checked caller and result consumer — observed

Record-field validation passes decoded names to StronglyUniqueNameSet::add and turns duplicate=true into a not-strongly-unique decoder failure. Import validation does the same, then checks annotations before adding the import.

- [js/src/wasm/WasmValidate.cpp:5293–5310](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmValidate.cpp#L5293-L5310), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
      for (uint32_t i = 0; i < numFields; i++) {
        CacheableName name;
        if (!DecodeComponentNameNoAttributes(d, "record field", &name)) {
```

- [js/src/wasm/WasmValidate.cpp:6898–6935](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmValidate.cpp#L6898-L6935), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
  ComponentName importName;
  if (!DecodeComponentName(d, "import", &importName)) {
    return false;
```


### 2. name contract — observed

The header requires a valid component-model name; StronglyUniqueNameSet owns canonicalized keys. Character-only assertions in this source do not establish the complete valid-name grammar.

- [js/src/wasm/WasmComponent.h:395–398](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.h#L395-L398), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
// Takes a valid component-model name and creates a "canonical" version of it
// that can be used to check strong uniqueness.
[[nodiscard]] bool CanonicalizeName(mozilla::Span<const char> name,
```

- [js/src/wasm/WasmComponent.h:437–446](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmComponent.h#L437-L446), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
// A class which can be used to check if a set of component model names is
// strongly-unique. The set owns its keys.
class StronglyUniqueNameSet {
```


### 3. cleanup caller — observed

wasm::ShutDown purges canonical component types only when no live JSRuntime remains and ENABLE_WASM_COMPONENTS is set.

- [js/src/wasm/WasmProcess.cpp:368–381](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/wasm/WasmProcess.cpp#L368-L381), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
void wasm::ShutDown() {
  // If there are live runtimes then we are already pretty much leaking the
  // world, so to avoid spurious assertions (which are valid and valuable when
```


## Tests and what they check

No product test was run for this record. A direct assertion below is a source-verified check, not a PASS result.

### possible-needs-check

Test source invokes wasmFailValidateText with not-strongly-unique regex for case, hyphen and attribute-related collisions. Helper implementation was not checked within this packet, so the direct assertion chain is not yet certified.

Limits: Not run; skipped when wasmComponentsEnabled is false. Does not cover every body in this source.

- [js/src/jit-test/tests/wasm/components/strongly-unique.js:24–41](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/jit-test/tests/wasm/components/strongly-unique.js#L24-L41), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
function assertNotStronglyUnique(badName) {
  wasmFailValidateText(`(component
    ${specOkImports}
```

- [js/src/jit-test/tests/wasm/components/directives.txt:1–1](https://github.com/mozilla/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/js/src/jit-test/tests/wasm/components/directives.txt#L1-L1), revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```
|jit-test| test-also=-P wasm_components; test-also=--wasm-compiler=baseline -P wasm_components; test-also=--wasm-compiler=optimizing -P wasm_components; include:wasm.js
```


## Search and reuse limits

- {"command": "git grep -n -e StronglyUniqueNameSet -e CanonicalizeName -e PurgeComponentCanonicalTypes PIN -- js/src", "scope": "Pinned JS engine source", "result": "Found validation callers and process-shutdown cleanup. One unrelated historical test string named NWDSCanonicalizeName was rejected as a name-only match."}
- {"command": "git grep -n -i -e strongly unique -e duplicate.*name -e canonical PIN -- js/src/jit-test/tests/wasm/components", "scope": "Component-model tests", "result": "Found names/types/import-export/canonical ABI tests; read strongly-unique.js and directives."}
- {"command": "rg -l WasmComponent.cpp|StronglyUniqueNameSet thunderbird-knowledge/notes", "scope": "Shared notes", "result": "Four structural records; no full prior body closure reused."}

Reused record IDs: None recorded.

This is a new immutable observation. Existing maps and claims retain their original scope. A matching name alone does not establish a runtime receiver. Unresolved links above require later source work.
