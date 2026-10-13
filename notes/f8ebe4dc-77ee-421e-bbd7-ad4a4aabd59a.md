<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:17:22.071Z","paths":["mail/components/calendar/test/browser/browser_calendarEventCreateEditDialog.js","mail/components/calendar/test/browser/browser_calendarEventCreateEditDialogRouting.js","mail/components/calendar/test/browser/browser_calendarEventCreateSave.js","mail/components/calendar/test/browser/browser_calendarEventEditSave.js","mail/components/calendar/test/browser/browser_positionedDialog.js","mail/components/calendar/test/browser/head.js","mail/components/calendar/test/unit/test_calendarAttachmentUtils.js","mail/components/calendar/test/unit/test_calendarEventCalendarState.js","mail/components/calendar/test/unit/test_calendarEventCreateEditState.js","mail/components/calendar/test/unit/test_calendarEventCreateSave.js","mail/components/calendar/test/unit/test_calendarEventDialogRouteController.js","mail/components/calendar/test/unit/test_calendarEventEditSave.js","mail/components/calendar/test/unit/test_calendarEventSourceState.js","mail/components/calendar/test/unit/test_dialog_position.js","mail/components/calendar/test/unit/test_joinLinkParser.js","mail/components/cloudfile/cloudFileAccounts.sys.mjs","mail/components/cloudfile/content/selectDialog.js","mail/components/cloudfile/test/browser/browser_repeat_upload.js","mail/components/cloudfile/test/browser/head.js","mail/components/compose/composer.js","mail/components/compose/content/ComposerCommands.js","mail/components/compose/content/MsgComposeCommands.js","mail/components/compose/content/addressingWidgetOverlay.js","mail/components/compose/content/bigFileObserver.js","mail/components/compose/content/cloudAttachmentLinkManager.js","mail/components/compose/content/composeWidgets.mjs","mail/components/compose/content/dialogs/EdAEAttributes.js","mail/components/compose/content/dialogs/EdAECSSAttributes.js","mail/components/compose/content/dialogs/EdAEHTMLAttributes.js","mail/components/compose/content/dialogs/EdAEJSEAttributes.js","mail/components/compose/content/dialogs/EdAdvancedEdit.js","mail/components/compose/content/dialogs/EdColorPicker.js","mail/components/compose/content/dialogs/EdColorProps.js","mail/components/compose/content/dialogs/EdConvertToTable.js","mail/components/compose/content/dialogs/EdDialogCommon.js","mail/components/compose/content/dialogs/EdDictionary.js","mail/components/compose/content/dialogs/EdHLineProps.js","mail/components/compose/content/dialogs/EdImageDialog.js","mail/components/compose/content/dialogs/EdImageLinkLoader.js","mail/components/compose/content/dialogs/EdImageProps.js","mail/components/compose/content/dialogs/EdInsSrc.js","mail/components/compose/content/dialogs/EdInsertChars.js","mail/components/compose/content/dialogs/EdInsertMath.js","mail/components/compose/content/dialogs/EdInsertTOC.js"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-study-20261013"}} -->
# thunderbird/mail JavaScript function map 25

Revision: `87d0159c7149a43253964c2cb6917939557dc799`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### mail/components/calendar/test/browser/browser_calendarEventCreateEditDialog.js

Blob: `cc37054b8f4be2ea2837cc71095e1e78fd9bafdb`. Role: test-path,source. Parse: module.

- (anonymous) @22-69; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-68; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForNextSourceLoad @71-86; FunctionDeclaration; parameters=1; async=false; generator=false
- element.onCalendarEventSourceLoaded @74-82; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @83-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForNextSourceError @88-98; FunctionDeclaration; parameters=1; async=false; generator=false
- element.onCalendarEventRouteError @91-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @95-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForMode @100-105; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @102-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- resetToCreateMode @107-110; FunctionDeclaration; parameters=1; async=true; generator=false
- closeDialog @112-127; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @122-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertCenteredInCalendarView @129-155; FunctionDeclaration; parameters=1; async=false; generator=false
- createAdditionalDialog @157-165; FunctionDeclaration; parameters=0; async=true; generator=false
- delayCalendarEventLoad @167-194; FunctionDeclaration; parameters=1; async=false; generator=false
- calendarObject.getItem @174-180; ArrowFunctionExpression; parameters=1; async=true; generator=false
- release @183-186; FunctionExpression; parameters=0; async=false; generator=false
- restore @187-189; FunctionExpression; parameters=0; async=false; generator=false
- waitForRequest @190-192; FunctionExpression; parameters=0; async=false; generator=false
- test_registrationAndStructure @196-235; FunctionExpression; parameters=0; async=true; generator=false
- test_sharedRowAndSubviewScaffolding @237-247; FunctionExpression; parameters=0; async=true; generator=false
- test_accessibleStaticDialogShell @249-263; FunctionExpression; parameters=0; async=true; generator=false
- test_dialogVisibilityChecks @265-286; FunctionExpression; parameters=0; async=true; generator=false
- test_dialogHasMinimumWidth @288-302; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @293-293; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_bodyScrollsWhenContentIsTooTall @304-444; FunctionExpression; parameters=0; async=true; generator=false
- test_rowsExpandAndCollapseWithinAvailableSpace @446-495; FunctionExpression; parameters=0; async=true; generator=false
- test_rowsScrollWhenAvailableSpaceIsConstrained @497-564; FunctionExpression; parameters=0; async=true; generator=false
- test_createRouteDoesNotLoadASourceEvent @565-591; FunctionExpression; parameters=0; async=true; generator=false
- dialog.onCalendarEventSourceLoaded @570-573; ArrowFunctionExpression; parameters=1; async=true; generator=false
- testCreateRouteAnchorsToCalendarTargets @593-651; FunctionExpression; parameters=0; async=true; generator=false
- testCreateRouteWithoutCalendarTargetCenters @653-687; FunctionExpression; parameters=0; async=true; generator=false
- testCreateRouteKeepsItsOpenPositionWhenScrolled @689-719; FunctionExpression; parameters=0; async=true; generator=false
- test_attributeDrivenSourceLoader @721-790; FunctionExpression; parameters=0; async=true; generator=false
- test_atomicRouteUpdatesClearModeAndRecurrence @792-828; FunctionExpression; parameters=0; async=true; generator=false
- test_loadingStateDrivesEditPresentation @830-867; FunctionExpression; parameters=0; async=true; generator=false
- dialog.onCalendarEventSourceLoaded @836-839; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_supersededSourceHookCannotApplyStaleState @869-924; FunctionExpression; parameters=0; async=true; generator=false
- dialog.onCalendarEventSourceLoaded @879-891; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_staleCalendarLookupCannotReplaceCurrentRoute @926-973; FunctionExpression; parameters=0; async=true; generator=false
- dialog.onCalendarEventSourceLoaded @933-938; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_dialogSessionsAreIsolatedAndReloadedAfterClose @975-1039; FunctionExpression; parameters=0; async=true; generator=false
- test_createAndEditDraftLifecycle @1041-1117; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1068-1068; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1102-1102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_showWaitsForTheCurrentSourceRoute @1119-1136; FunctionExpression; parameters=0; async=true; generator=false
- test_incompleteSourceIdentityIsNotLoaded @1138-1164; FunctionExpression; parameters=0; async=true; generator=false
- test_missingOrInvalidSourceFailuresAreControlled @1166-1243; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/mail/AxeHelpers.sys.mjs @7; ChromeUtils-import-literal

### mail/components/calendar/test/browser/browser_calendarEventCreateEditDialogRouting.js

Blob: `4ff85cbfce4b21230a7aa50707d8dbadd73a37e1`. Role: test-path,source. Parse: module.

- (anonymous) @23-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @45-53; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getCreateEditDialog @56-58; FunctionDeclaration; parameters=0; async=false; generator=false
- assertNewEventRoute @60-81; FunctionDeclaration; parameters=2; async=false; generator=false
- assertEditEventRoute @83-95; FunctionDeclaration; parameters=3; async=false; generator=false
- waitForCreateEditDialogOpen @97-123; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- closeCreateEditDialog @125-140; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @135-135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- closeLegacyEventDialog @142-146; FunctionDeclaration; parameters=1; async=true; generator=false
- test_prefEnabledRoutesEventsByIdentity @148-191; FunctionExpression; parameters=0; async=true; generator=false
- test_newEventControlsRouteToDialog @193-245; FunctionExpression; parameters=0; async=true; generator=false
- test_templateEventRouteHasNoIdentity @247-261; FunctionExpression; parameters=0; async=true; generator=false
- test_viewCreateAndEditRoutes @263-297; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @285-288; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @287-287; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_editEventCommandsRouteToDialog @299-352; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @312-315; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_prefDisabledUsesLegacyEventDialog @354-374; FunctionExpression; parameters=0; async=true; generator=false
- test_tabEditingAndTodosKeepLegacyRoutes @376-419; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/mail/AxeHelpers.sys.mjs @9; ChromeUtils-import-literal
- Module resource:///modules/CalTodo.sys.mjs @12; ChromeUtils-import-literal

### mail/components/calendar/test/browser/browser_calendarEventCreateSave.js

Blob: `b9a8093f13c6f080abcdea145a7d738fd23b6522`. Role: test-path,source. Parse: module.

- (anonymous) @26-144; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transaction @43-44; ArrowFunctionExpression; parameters=3; async=false; generator=false
- browser.contentWindow.doTransaction @45-52; ArrowFunctionExpression; parameters=6; async=false; generator=false
- (anonymous) @75-80; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @81-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- validate @87-93; FunctionExpression; parameters=1; async=false; generator=false
- apply @94-96; ArrowFunctionExpression; parameters=2; async=false; generator=false
- validate @100-105; ArrowFunctionExpression; parameters=1; async=false; generator=false
- apply @106-118; FunctionExpression; parameters=2; async=false; generator=false
- apply @122-122; ArrowFunctionExpression; parameters=2; async=false; generator=false
- remove @123-123; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-143; ArrowFunctionExpression; parameters=0; async=true; generator=false
- create @147-177; FunctionDeclaration; parameters=1; async=true; generator=false
- snapshot @155-159; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_keyboardSaveSelectedCalendarAndUndoRedo @179-243; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @209-212; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onAddItem @217-217; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDeleteItem @218-218; FunctionExpression; parameters=0; async=false; generator=false
- test_invalidFieldsKeepValuesAndDisplayErrors @245-312; FunctionExpression; parameters=0; async=true; generator=false
- transaction @250-252; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @264-267; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @297-305; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_rowTogglePendingFailureAndKeyboardRetry @314-398; FunctionExpression; parameters=0; async=true; generator=false
- transaction @328-334; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @335-338; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @370-370; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onAddItem @379-379; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDeleteItem @380-380; FunctionExpression; parameters=0; async=false; generator=false
- test_staleCreateResultsKeepReplacementDialog @400-441; FunctionExpression; parameters=0; async=true; generator=false
- transaction @406-411; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_productionSaveAddsRenderedCalendarEvent @443-499; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @455-458; ArrowFunctionExpression; parameters=0; async=false; generator=false
- validate @461-461; ArrowFunctionExpression; parameters=1; async=false; generator=false
- snapshot @469-473; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findEvent @481-484; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @483-483; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @488-488; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/mail/AxeHelpers.sys.mjs @7; ChromeUtils-import-literal
- Module resource:///modules/CalTransactionManager.sys.mjs @10; ChromeUtils-import-literal

### mail/components/calendar/test/browser/browser_calendarEventEditSave.js

Blob: `0bc894b34489827deaca51c25189bfcccd1cfb74`. Role: test-path,source. Parse: module.

- (anonymous) @21-73; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transaction @38-46; ArrowFunctionExpression; parameters=3; async=false; generator=false
- browser.contentWindow.promptOccurrenceModification @47-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- browser.contentWindow.doTransaction @48-55; ArrowFunctionExpression; parameters=6; async=false; generator=false
- (anonymous) @62-72; ArrowFunctionExpression; parameters=0; async=true; generator=false
- edit @76-85; FunctionDeclaration; parameters=2; async=true; generator=false
- test_keyboardSaveClearsStateAndUpdatesCalendar @87-152; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @118-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_pendingSaveLocksRouteAndFailureKeepsFocusAndDraft @155-255; FunctionExpression; parameters=0; async=true; generator=false
- transaction @164-169; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @170-173; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-191; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @230-230; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_cancelAndMoveNotifications @258-289; FunctionExpression; parameters=0; async=true; generator=false
- transaction @268-271; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @272-274; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_occurrenceRouteLoadsBeforeSave @291-319; FunctionExpression; parameters=0; async=true; generator=false
- test_productionSaveUpdatesRenderedCalendarView @321-369; FunctionExpression; parameters=0; async=true; generator=false
- findEvent @337-340; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @339-339; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @342-342; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @350-353; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @358-358; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_separateDocumentsSaveAfterCalendarMove @371-489; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @381-383; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @384-385; ArrowFunctionExpression; parameters=1; async=false; generator=false
- secondWindow.promptOccurrenceModification @392-392; ArrowFunctionExpression; parameters=1; async=false; generator=false
- secondWindow.doTransaction @406-418; ArrowFunctionExpression; parameters=6; async=true; generator=false
- transaction @419-423; ArrowFunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @424-428; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @432-432; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @433-433; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @445-445; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @446-446; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @454-454; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transaction @460-467; ArrowFunctionExpression; parameters=3; async=false; generator=false
- test_pendingStatusHasNoBusyAncestor @491-537; FunctionExpression; parameters=0; async=true; generator=false
- transaction @497-501; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @517-517; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @520-521; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @525-525; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_escapeDismissesReadyAndFailedButNotPending @539-602; FunctionExpression; parameters=0; async=true; generator=false
- transaction @551-555; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_nativeCloseRequestsKeepReturnValues @604-625; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/mail/AxeHelpers.sys.mjs @7; ChromeUtils-import-literal
- Module resource:///modules/CalTransactionManager.sys.mjs @10; ChromeUtils-import-literal

### mail/components/calendar/test/browser/browser_positionedDialog.js

Blob: `ca205085c4be9fef8c9b9359403def2b5bc38a42`. Role: test-path,source. Parse: module.

- (anonymous) @14-37; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupPositioning @52-80; FunctionDeclaration; parameters=1; async=true; generator=false
- test_positionedDialogPosition @1275-1290; FunctionExpression; parameters=0; async=true; generator=false

### mail/components/calendar/test/browser/head.js

Blob: `d35d250f95d8e8413f49950c352f2bab0fc548ee`. Role: test-path,source. Parse: module.

- createCalendar @114-132; FunctionDeclaration; parameters=1; async=false; generator=false
- createEvent @157-226; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @209-211; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openEvent @234-253; FunctionDeclaration; parameters=1; async=true; generator=false
- showEvent @269-304; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @299-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openAndShowEvent @320-328; FunctionDeclaration; parameters=1; async=true; generator=false
- waitForCalendarReady @333-342; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @340-340; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkTolerance @352-469; FunctionDeclaration; parameters=3; async=false; generator=false
- resizeWindow @483-505; FunctionDeclaration; parameters=1; async=true; generator=false
- debounceCallback @486-490; FunctionDeclaration; parameters=0; async=false; generator=false
- positionTest @516-548; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @542-542; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupPositioning @553-568; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @565-567; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testDurations @575-591; FunctionDeclaration; parameters=1; async=true; generator=false
- runPositioningTest @598-614; FunctionDeclaration; parameters=1; async=true; generator=false
- createAlarmFromDuration @622-629; FunctionDeclaration; parameters=1; async=false; generator=false
- Module resource:///modules/CalEvent.sys.mjs @7; ChromeUtils-import-literal
- Module resource:///modules/CalAttendee.sys.mjs @10; ChromeUtils-import-literal
- Module resource:///modules/calendar/calUtils.sys.mjs @13; ChromeUtils-import-literal
- Module resource://testing-common/calendar/CalendarTestUtils.sys.mjs @16; ChromeUtils-import-literal
- Module resource:///modules/CalRecurrenceInfo.sys.mjs @19; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/positioned-dialog.mjs @22; ChromeUtils-import-literal
- Module resource:///modules/CalAlarm.sys.mjs @26; ChromeUtils-import-literal
- Module resource:///modules/CalAttachment.sys.mjs @30; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarAttachmentUtils.js

Blob: `bcedf1258fa34d7b58daf63e97b351d682625288`. Role: test-path,source. Parse: module.

- test_getAttachmentIcon_emptyAttachment @13-23; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_aboutBlankAttachment @25-36; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_fileURI @38-51; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_formatType @53-66; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_serviceIconURL @68-80; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_remoteGuess @82-95; FunctionExpression; parameters=0; async=false; generator=false
- test_getAttachmentIcon_fallback @97-108; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///comm/mail/components/calendar/modules/CalendarAttachmentUtils.sys.mjs @5; ChromeUtils-import-literal
- Module resource:///modules/CalAttachment.sys.mjs @9; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventCalendarState.js

Blob: `6a78973ec7152f0bdd76635eb6c85dc089ac1e1b`. Role: test-path,source. Parse: module.

- test_no_selection_is_disabled @29-33; FunctionExpression; parameters=0; async=false; generator=false
- test_move_requires_more_than_edit_permission @35-76; FunctionExpression; parameters=0; async=false; generator=false
- getProperty @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- event.calendar.getSchedulingSupport @71-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isInvitation @71-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startSelection @78-91; FunctionDeclaration; parameters=2; async=false; generator=false
- test_selection_only_changes_current_draft_calendar @93-135; FunctionExpression; parameters=0; async=false; generator=false
- test_stale_and_unavailable_selections_are_ignored @137-173; FunctionExpression; parameters=0; async=false; generator=false
- test_field_defaults_preserve_other_changes @175-205; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///comm/mail/base/content/state/store.mjs @5; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventCalendarSlice.mjs @9; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventDraftSlice.mjs @17; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendar-event-create-edit-selectors.mjs @21; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-calendar-options.mjs @36; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventCreateEditState.js

Blob: `b99ad409b607ba878317dcaba6cc80b4869eee85`. Role: test-path,source. Parse: module.

- sourceSnapshot @40-66; FunctionDeclaration; parameters=0; async=false; generator=false
- reduceDraft @68-70; FunctionDeclaration; parameters=2; async=false; generator=false
- test_sessionSliceIsInjectedIntoTheApplicationStore @72-80; FunctionExpression; parameters=0; async=false; generator=false
- test_sourceSnapshotStartsAnIsolatedDraft @82-143; FunctionExpression; parameters=0; async=false; generator=false
- test_createDraftAcceptsProviderValuesWithoutDefaults @145-170; FunctionExpression; parameters=0; async=false; generator=false
- test_dateTimeSectionStaysDirtyUntilBothValuesMatchBaseline @172-239; FunctionExpression; parameters=0; async=false; generator=false
- test_dirtySectionsAndValidationResetForNewSource @241-296; FunctionExpression; parameters=0; async=false; generator=false
- test_selectorsReflectDraftAndOperationState @298-402; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventDraftSlice.mjs @13; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventCreateEditSessionSlice.mjs @23; ChromeUtils-import-literal
- Module moz-src:///comm/mail/base/content/state/store.mjs @26; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendar-event-create-edit-selectors.mjs @34; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventCreateSave.js

Blob: `929d170ee0f85baa629302197b387801f5c99778`. Role: test-path,source. Parse: module.

- validate @54-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- apply @58-60; ArrowFunctionExpression; parameters=2; async=false; generator=false
- validate @64-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- apply @71-82; FunctionExpression; parameters=2; async=false; generator=false
- validate @86-86; ArrowFunctionExpression; parameters=1; async=false; generator=false
- apply @87-87; ArrowFunctionExpression; parameters=2; async=false; generator=false
- remove @88-88; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @92-109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startCreate @112-136; FunctionDeclaration; parameters=1; async=false; generator=false
- save @139-152; FunctionDeclaration; parameters=1; async=false; generator=false
- transact @144-149; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_createSelectedCalendarAndUndoRedo @154-215; FunctionExpression; parameters=0; async=true; generator=false
- onAddItem @167-167; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDeleteItem @168-168; FunctionExpression; parameters=0; async=false; generator=false
- dispatch @174-177; FunctionExpression; parameters=1; async=false; generator=false
- test_validationRetainsDraftAndStartsNoTransaction @217-278; FunctionExpression; parameters=0; async=true; generator=false
- transact @231-233; ArrowFunctionExpression; parameters=0; async=false; generator=false
- transact @256-257; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_duplicateFailureAndDisabledRowRetry @280-353; FunctionExpression; parameters=0; async=true; generator=false
- transact @316-321; ArrowFunctionExpression; parameters=1; async=true; generator=false
- onAddItem @341-341; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDeleteItem @342-342; FunctionExpression; parameters=0; async=false; generator=false
- test_staleResultsKeepReplacementDraftAndSession @355-413; FunctionExpression; parameters=0; async=true; generator=false
- transact @361-366; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_rowStateDefaultsChangesAndReset @415-454; FunctionExpression; parameters=0; async=true; generator=false
- test_pendingSuccessCreatesOnlyOneEvent @456-481; FunctionExpression; parameters=0; async=true; generator=false
- transact @462-470; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_replacementDuringValidationStartsNoTransaction @483-528; FunctionExpression; parameters=0; async=true; generator=false
- dispatch @489-500; FunctionExpression; parameters=1; async=false; generator=false
- transact @507-509; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_calendarAccessAndConversionFailureRetainDraft @530-580; FunctionExpression; parameters=0; async=true; generator=false
- transact @542-543; ArrowFunctionExpression; parameters=0; async=false; generator=false
- apply @562-564; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_calendarFieldValidationIsNotOverwritten @582-616; FunctionExpression; parameters=0; async=true; generator=false
- validate @592-595; ArrowFunctionExpression; parameters=0; async=false; generator=false
- apply @596-597; ArrowFunctionExpression; parameters=0; async=false; generator=false
- transact @600-602; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/calendar/calUtils.sys.mjs @7; ChromeUtils-import-literal
- Module resource://testing-common/AppInfo.sys.mjs @10; ChromeUtils-import-literal
- Module resource:///modules/CalTransactionManager.sys.mjs @13; ChromeUtils-import-literal
- Module moz-src:///comm/mail/base/content/state/store.mjs @16; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventDraftSlice.mjs @27; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventCreateEditSessionSlice.mjs @34; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendar-event-create-edit-selectors.mjs @37; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-create-save.mjs @40; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-save-fields.mjs @43; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventDialogRouteController.js

Blob: `98ab8b96d6199e22d0bf602f18098785a2e5e29d`. Role: test-path,source. Parse: module.

- createFrameScheduler @9-34; FunctionDeclaration; parameters=0; async=false; generator=false
- cancelAnimationFrame @14-16; FunctionExpression; parameters=1; async=false; generator=false
- requestAnimationFrame @18-22; FunctionExpression; parameters=1; async=false; generator=false
- frameCount @24-26; FunctionExpression; parameters=0; async=false; generator=false
- runNextFrame @28-32; FunctionExpression; parameters=0; async=false; generator=false
- test_stale_route_cannot_finish_replacement @36-63; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @40-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_disconnect_cancels_scheduled_route @65-80; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @69-71; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-dialog-route-controller.mjs @5; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventEditSave.js

Blob: `8afce1ada185a7ec1e969e8596082cc170e43b5a`. Role: test-path,source. Parse: module.

- apply @68-70; FunctionExpression; parameters=2; async=false; generator=false
- remove @71-73; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @76-93; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createEvent @96-110; FunctionDeclaration; parameters=1; async=true; generator=false
- startEdit @113-130; FunctionDeclaration; parameters=3; async=true; generator=false
- changeTitle @132-136; FunctionDeclaration; parameters=2; async=false; generator=false
- save @139-152; FunctionDeclaration; parameters=1; async=false; generator=false
- chooseOccurrence @143-143; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transact @144-149; ArrowFunctionExpression; parameters=2; async=false; generator=false
- saveWithDuplicateId @163-184; FunctionDeclaration; parameters=1; async=true; generator=false
- provider.notifyError @167-170; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @178-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_editAndMoveUndoRedo @186-253; FunctionExpression; parameters=0; async=true; generator=false
- onModifyItem @201-201; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @203-203; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_failureDuplicateAndDisabledRowRetry @255-349; FunctionExpression; parameters=0; async=true; generator=false
- transact @288-298; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_staleSuccessAndFailureCannotUpdateReplacement @351-380; FunctionExpression; parameters=0; async=true; generator=false
- transact @360-366; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_overlappingEditsKeepNewestValues @382-414; FunctionExpression; parameters=0; async=true; generator=false
- transact @392-400; ArrowFunctionExpression; parameters=2; async=true; generator=false
- test_overlappingEditsAfterCalendarMove @416-498; FunctionExpression; parameters=0; async=true; generator=false
- transact @437-445; ArrowFunctionExpression; parameters=2; async=true; generator=false
- transact @450-459; ArrowFunctionExpression; parameters=2; async=true; generator=false
- transact @471-479; ArrowFunctionExpression; parameters=2; async=true; generator=false
- test_calendarMoveQueueFailureAndCleanup @500-545; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @507-507; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @511-517; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @520-523; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @529-529; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @538-538; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_destinationEditWaitsForMoveCompletion @547-601; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @559-563; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @564-570; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @573-580; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_calendarCopiesKeepTheirOwnLiveEvents @603-636; FunctionExpression; parameters=0; async=true; generator=false
- transact @616-624; ArrowFunctionExpression; parameters=2; async=true; generator=false
- test_occurrenceScopeAndCancel @638-677; FunctionExpression; parameters=0; async=true; generator=false
- chooseOccurrence @651-651; ArrowFunctionExpression; parameters=0; async=false; generator=false
- chooseOccurrence @667-667; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_livePermissionsAndUnavailableSource @679-705; FunctionExpression; parameters=0; async=true; generator=false
- test_rowDefaultsAndDirtyStateStaySeparate @707-777; FunctionExpression; parameters=0; async=true; generator=false
- test_dateChangesAndWholeSeriesShift @779-834; FunctionExpression; parameters=0; async=true; generator=false
- chooseOccurrence @800-800; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_itemAndMovePermissionsAreCheckedAtSave @836-874; FunctionExpression; parameters=0; async=true; generator=false
- test_transactionsKeepNotificationDataAndResultsSerializable @877-918; FunctionExpression; parameters=0; async=true; generator=false
- cal.itip.checkAndSend @883-883; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @884-886; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getState @890-890; ArrowFunctionExpression; parameters=0; async=false; generator=false
- dispatch @891-894; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transact @896-901; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_failedMoveRollsBackStorageAndNotifications @921-990; FunctionExpression; parameters=0; async=true; generator=false
- sourceCalendar.deleteItem @938-940; ArrowFunctionExpression; parameters=0; async=true; generator=false
- cal.itip.checkAndSend @941-941; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @978-978; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_staleDraftResultsReleaseOnlyTheirOwnRequest @992-1086; FunctionExpression; parameters=0; async=true; generator=false
- transact @1002-1013; ArrowFunctionExpression; parameters=2; async=true; generator=false
- test_queuedOccurrencesFollowWholeSeriesShifts @1088-1206; FunctionExpression; parameters=0; async=true; generator=false
- chooseOccurrence @1142-1142; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transact @1143-1151; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1155-1159; ArrowFunctionExpression; parameters=1; async=false; generator=false
- chooseOccurrence @1163-1163; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_queuedSeriesEditsKeepLocalTimeAcrossDaylightSaving @1209-1312; FunctionExpression; parameters=0; async=true; generator=false
- chooseOccurrence @1275-1275; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transact @1276-1284; ArrowFunctionExpression; parameters=2; async=true; generator=false
- chooseOccurrence @1289-1289; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_queuedWeeklyOccurrenceFollowsUpdatedRule @1315-1395; FunctionExpression; parameters=0; async=true; generator=false
- transact @1349-1357; ArrowFunctionExpression; parameters=2; async=true; generator=false
- test_failedMoveCleanupCanRetryWithStorage @1397-1527; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1404-1404; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cal.itip.checkAndSend @1412-1412; ArrowFunctionExpression; parameters=1; async=false; generator=false
- sourceProvider.deleteItem @1432-1434; ArrowFunctionExpression; parameters=0; async=true; generator=false
- targetProvider.deleteItem @1435-1437; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1498-1498; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1508-1508; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_moveRollbackPreservesPendingDestinationEdits @1529-1661; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1536-1536; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cal.itip.checkAndSend @1541-1541; ArrowFunctionExpression; parameters=1; async=false; generator=false
- sourceProvider.deleteItem @1559-1563; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1628-1628; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource:///modules/calendar/calUtils.sys.mjs @7; ChromeUtils-import-literal
- Module resource://testing-common/TestUtils.sys.mjs @10; ChromeUtils-import-literal
- Module resource://testing-common/AppInfo.sys.mjs @13; ChromeUtils-import-literal
- Module resource:///modules/calendar/CalendarEventEdit.sys.mjs @16; ChromeUtils-import-literal
- Module resource:///modules/CalTransactionManager.sys.mjs @20; ChromeUtils-import-literal
- Module moz-src:///comm/mail/base/content/state/store.mjs @23; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendar-event-source-state.mjs @27; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventDraftSlice.mjs @35; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/state/calendarEventCreateEditSessionSlice.mjs @42; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-edit-save.mjs @45; ChromeUtils-import-literal
- Module moz-src:///comm/mail/components/calendar/content/calendar-event-save-fields.mjs @48; ChromeUtils-import-literal
- Module resource:///modules/CalEvent.sys.mjs @52; ChromeUtils-import-literal
- Module resource:///modules/CalAttendee.sys.mjs @55; ChromeUtils-import-literal
- Module resource:///modules/CalRecurrenceInfo.sys.mjs @58; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_calendarEventSourceState.js

Blob: `39588f905bdbbdc8a419cb941c15f19853483590`. Role: test-path,source. Parse: module.

- reduceSource @25-27; FunctionDeclaration; parameters=2; async=false; generator=false
- sourceSnapshot @29-43; FunctionDeclaration; parameters=0; async=false; generator=false
- test_source_session_is_selected_from_the_injected_slice @45-79; FunctionExpression; parameters=0; async=false; generator=false
- test_stale_source_result_does_not_replace_current_session @81-144; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///comm/mail/components/calendar/content/state/calendar-event-source-state.mjs @11; ChromeUtils-import-literal
- Module moz-src:///comm/mail/base/content/state/store.mjs @14; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_dialog_position.js

Blob: `b4699d9390e53832cfb20c96af9227cf01d9b9b0`. Role: test-path,source. Parse: module.

- test_dialogPosition @1314-1321; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///comm/mail/components/calendar/content/dialog-position.mjs @7; ChromeUtils-import-literal

### mail/components/calendar/test/unit/test_joinLinkParser.js

Blob: `59da2e20fb70c229ca003c2022180d1b922a7662`. Role: test-path,source. Parse: module.

- test_noJoinkLink @182-187; FunctionExpression; parameters=0; async=false; generator=false
- test_providerJoinLinks @189-200; FunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/calendar/JoinLinkParser.sys.mjs @7; ChromeUtils-import-literal

### mail/components/cloudfile/cloudFileAccounts.sys.mjs

Blob: `2c0e79848bdd054cfd5887ba5111f94bdafdd333`. Role: source. Parse: module.

- constants @10-26; FunctionExpression; parameters=0; async=false; generator=false
- constructor @28-33; FunctionExpression; parameters=0; async=false; generator=false
- _accountKeys @35-52; FunctionExpression; parameters=0; async=false; generator=false
- _ensureKey @61-69; FunctionExpression; parameters=1; async=false; generator=false
- registerProvider @77-83; FunctionExpression; parameters=2; async=false; generator=false
- unregisterProvider @90-101; FunctionExpression; parameters=1; async=false; generator=false
- providers @103-105; FunctionExpression; parameters=0; async=false; generator=false
- getProviderForType @107-109; FunctionExpression; parameters=1; async=false; generator=false
- createAccount @111-136; FunctionExpression; parameters=1; async=false; generator=false
- removeAccount @138-150; FunctionExpression; parameters=1; async=false; generator=false
- accounts @152-161; FunctionExpression; parameters=0; async=false; generator=false
- configuredAccounts @163-165; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @164-164; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAccount @171-186; FunctionExpression; parameters=1; async=false; generator=false
- getAccountsForType @188-201; FunctionExpression; parameters=1; async=false; generator=false
- getDisplayName @203-207; FunctionExpression; parameters=1; async=false; generator=false
- setDisplayName @209-215; FunctionExpression; parameters=2; async=false; generator=false
- Class (anonymous) @9-216
- Module resource://gre/modules/EventEmitter.sys.mjs @7; ImportDeclaration

### mail/components/cloudfile/content/selectDialog.js

Blob: `28edda5d3ead16b4e2f058558d82d16cc2f2dac8`. Role: source. Parse: module.

- (anonymous) @7-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cloudfileDialogOnLoad @11-21; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/cloudfile/test/browser/browser_repeat_upload.js

Blob: `0be05e73822c1317b00fa6cbb8dcddb8ad8fafbe`. Role: test-path,source. Parse: module.

- getFileFromChromeURL @14-26; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @28-248; ArrowFunctionExpression; parameters=0; async=true; generator=false
- initAccount @34-55; FunctionExpression; parameters=1; async=false; generator=false
- displayName @38-43; FunctionExpression; parameters=0; async=false; generator=false
- getPreviousUploads @44-46; FunctionExpression; parameters=0; async=false; generator=false
- urlForFile @47-49; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @154-157; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @178-181; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @210-210; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/cloudFileAccounts.sys.mjs @7; ChromeUtils-import-literal

### mail/components/cloudfile/test/browser/head.js

Blob: `731d68068781aaaf07f5ad09b74f5d6fadb43446`. Role: test-path,source. Parse: module.

- (anonymous) @9-17; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createAccount @19-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cleanUpAccount @30-33; FunctionDeclaration; parameters=1; async=false; generator=false
- addIdentity @35-41; FunctionDeclaration; parameters=1; async=false; generator=false
- promiseAnimationFrame @43-47; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource:///modules/MailServices.sys.mjs @5; ChromeUtils-import-literal

### mail/components/compose/composer.js

Blob: `68e94cdc55ccfb3f65683f9dacabc761cfea73fa`. Role: source. Parse: failed.

Failure: Unexpected token #filter


### mail/components/compose/content/ComposerCommands.js

Blob: `9c67fbccab68b525e1b6bc4936f15b580ab0051e`. Role: source. Parse: module.

- SetupHTMLEditorCommands @41-132; FunctionDeclaration; parameters=0; async=false; generator=false
- SetupTextEditorCommands @134-148; FunctionDeclaration; parameters=0; async=false; generator=false
- GetComposerCommandTable @156-199; FunctionDeclaration; parameters=0; async=false; generator=false
- registerCommand @165-167; FunctionExpression; parameters=2; async=false; generator=false
- supportsCommand @168-170; FunctionExpression; parameters=1; async=false; generator=false
- isCommandEnabled @171-178; FunctionExpression; parameters=1; async=false; generator=false
- doCommand @179-181; FunctionExpression; parameters=1; async=false; generator=false
- getCommandStateWithParams @182-184; FunctionExpression; parameters=2; async=false; generator=false
- doCommandWithParams @185-187; FunctionExpression; parameters=2; async=false; generator=false
- goUpdateCommandState @207-269; FunctionDeclaration; parameters=1; async=false; generator=false
- goUpdateComposerMenuItems @282-294; FunctionDeclaration; parameters=1; async=false; generator=false
- goDoCommandParams @304-320; FunctionDeclaration; parameters=2; async=false; generator=false
- pokeStyleUI @329-356; FunctionDeclaration; parameters=2; async=false; generator=false
- doStyleUICommand @387-396; FunctionDeclaration; parameters=1; async=false; generator=false
- stringToTypedArray @399-405; FunctionDeclaration; parameters=1; async=false; generator=false
- pokeMultiStateUI @414-453; FunctionDeclaration; parameters=2; async=false; generator=false
- doStatefulCommand @464-507; FunctionDeclaration; parameters=3; async=false; generator=false
- isCommandEnabled @510-512; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @514-514; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @515-515; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @517-520; FunctionExpression; parameters=0; async=false; generator=false
- GetExtensionBasedOnMimeType @526-542; FunctionDeclaration; parameters=1; async=false; generator=false
- GetSuggestedFileName @544-573; FunctionDeclaration; parameters=2; async=false; generator=false
- PromptForSaveLocation @578-671; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @653-670; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @654-669; ArrowFunctionExpression; parameters=1; async=false; generator=false
- PromptAndSetTitleIfNone @680-702; FunctionDeclaration; parameters=0; async=false; generator=false
- OutputFileWithPersistAPI @711-782; FunctionDeclaration; parameters=4; async=false; generator=false
- GetOutputFlags @785-829; FunctionDeclaration; parameters=2; async=false; generator=false
- GetWrapColumn @832-837; FunctionDeclaration; parameters=0; async=false; generator=false
- IsSupportedTextMimeType @852-859; FunctionDeclaration; parameters=1; async=false; generator=false
- SaveDocument @862-1050; FunctionDeclaration; parameters=3; async=true; generator=false
- isCommandEnabled @1053-1055; FunctionExpression; parameters=2; async=false; generator=false
- getCommandStateParams @1057-1057; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1058-1058; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1060-1067; FunctionExpression; parameters=2; async=false; generator=false
- isCommandEnabled @1071-1073; FunctionExpression; parameters=2; async=false; generator=false
- getCommandStateParams @1075-1075; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1076-1076; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1078-1080; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1084-1088; FunctionExpression; parameters=2; async=false; generator=false
- getCommandStateParams @1090-1090; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1091-1091; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1093-1096; FunctionExpression; parameters=1; async=false; generator=false
- isCommandEnabled @1100-1106; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1108-1108; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1109-1109; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1111-1113; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1117-1121; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1123-1123; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1124-1124; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1126-1141; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1145-1147; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1149-1149; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1150-1150; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1152-1158; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1162-1164; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1166-1166; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1167-1167; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1169-1224; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1228-1230; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1232-1232; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1233-1233; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1235-1254; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1258-1260; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1262-1262; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1263-1263; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1265-1272; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1276-1278; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1280-1280; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1281-1281; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1283-1291; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1295-1297; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1299-1299; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1300-1300; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1302-1309; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1313-1315; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1317-1317; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1318-1318; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1320-1322; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1326-1328; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1330-1330; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1331-1331; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1333-1337; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1341-1343; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1345-1345; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1346-1346; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1348-1354; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1358-1366; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1368-1368; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1369-1369; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1371-1420; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1424-1426; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1428-1428; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1429-1438; FunctionExpression; parameters=2; async=false; generator=false
- doCommand @1440-1440; FunctionExpression; parameters=0; async=false; generator=false
- doAdvancedProperties @1443-1453; FunctionDeclaration; parameters=1; async=false; generator=false
- isCommandEnabled @1456-1458; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1460-1460; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1461-1461; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1463-1471; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1475-1481; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1483-1483; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1484-1484; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1486-1489; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1493-1499; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1501-1501; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1502-1502; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1504-1507; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1511-1514; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1516-1516; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1517-1517; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1519-1522; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1526-1528; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1530-1530; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1531-1531; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1533-1539; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1543-1545; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1547-1547; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1548-1548; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1550-1552; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1556-1558; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1560-1560; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1561-1561; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1563-1568; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1572-1574; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1576-1576; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1577-1577; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1579-1584; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1588-1590; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1592-1592; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1593-1593; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1595-1600; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1604-1606; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1608-1608; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1609-1609; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1611-1616; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1620-1622; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1624-1624; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1625-1625; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1627-1632; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1636-1638; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1640-1640; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1641-1641; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1643-1645; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1649-1651; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1653-1653; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1654-1654; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1656-1661; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1665-1667; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1669-1669; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1670-1670; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1672-1677; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1681-1683; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1685-1685; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1686-1686; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1688-1693; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1697-1699; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1701-1701; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1702-1702; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1704-1709; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1713-1715; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1717-1717; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1718-1718; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1720-1725; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1729-1731; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1733-1733; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1734-1734; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1736-1741; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1745-1747; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1749-1749; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1750-1750; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1752-1757; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1761-1763; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1765-1765; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1766-1766; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1768-1788; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1792-1794; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1796-1796; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1797-1797; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1799-1819; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1823-1825; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1827-1827; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1828-1828; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1830-1835; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1839-1841; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1843-1843; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1844-1844; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1846-1851; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1855-1898; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1900-1900; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1901-1901; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1903-1909; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1913-1945; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1947-1947; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1948-1948; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1950-1955; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1959-1961; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @1963-1963; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @1964-1964; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1966-1968; FunctionExpression; parameters=0; async=false; generator=false
- isCommandEnabled @1972-2010; FunctionExpression; parameters=0; async=false; generator=false
- getCommandStateParams @2012-2012; FunctionExpression; parameters=0; async=false; generator=false
- doCommandParams @2013-2013; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @2015-2023; FunctionExpression; parameters=0; async=false; generator=false

### mail/components/compose/content/MsgComposeCommands.js

Blob: `de7dd2ae28195677cbef1ba1a39ff2fb4e03e8ed`. Role: source. Parse: module.

- (anonymous) @101-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @114-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @278-280; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @281-284; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @285-289; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @290-292; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @293-295; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @296-300; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @302-306; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setOverLink @316-316; FunctionExpression; parameters=0; async=false; generator=false
- onBeforeLinkTraversal @319-321; FunctionExpression; parameters=1; async=false; generator=false
- showTooltip @324-342; FunctionExpression; parameters=4; async=false; generator=false
- hideTooltip @345-348; FunctionExpression; parameters=0; async=false; generator=false
- getTabCount @350-352; FunctionExpression; parameters=0; async=false; generator=false
- observe @362-378; ArrowFunctionExpression; parameters=2; async=false; generator=false
- observe @382-394; ArrowFunctionExpression; parameters=2; async=true; generator=false
- observe @398-413; FunctionExpression; parameters=2; async=false; generator=false
- InitializeGlobalVariables @421-456; FunctionDeclaration; parameters=0; async=false; generator=false
- ReleaseGlobalVariables @459-476; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @479-484; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @480-483; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getNextSibling @494-509; FunctionDeclaration; parameters=2; async=false; generator=false
- getPreviousSibling @519-534; FunctionDeclaration; parameters=2; async=false; generator=false
- getPrettyKey @542-544; FunctionDeclaration; parameters=1; async=false; generator=false
- updateEditableFields @554-588; FunctionDeclaration; parameters=1; async=false; generator=false
- isSignature @596-601; FunctionDeclaration; parameters=1; async=false; generator=false
- NotifyComposeFieldsReady @604-607; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeBodyReady @609-682; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeBodyReadyNew @684-740; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeBodyReadyReply @742-788; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeBodyReadyForwardInline @790-820; FunctionExpression; parameters=0; async=false; generator=false
- ComposeProcessDone @822-845; FunctionExpression; parameters=1; async=false; generator=false
- SaveInFolderDone @847-849; FunctionExpression; parameters=1; async=false; generator=false
- onStartSending @855-855; FunctionExpression; parameters=0; async=false; generator=false
- onSendProgress @856-856; FunctionExpression; parameters=0; async=false; generator=false
- onStatus @857-857; FunctionExpression; parameters=0; async=false; generator=false
- onStopSending @858-862; FunctionExpression; parameters=2; async=false; generator=false
- onGetDraftFolderURI @863-863; FunctionExpression; parameters=0; async=false; generator=false
- onSendNotPerformed @864-864; FunctionExpression; parameters=0; async=false; generator=false
- onTransportSecurityError @865-917; FunctionExpression; parameters=4; async=false; generator=false
- onWindowClosed @888-915; FunctionDeclaration; parameters=1; async=false; generator=false
- onStateChange @926-955; FunctionExpression; parameters=3; async=false; generator=false
- waitForStop @957-976; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @963-975; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onProgressStop @964-973; FunctionDeclaration; parameters=1; async=false; generator=false
- onProgressChange @978-1017; FunctionExpression; parameters=6; async=false; generator=false
- onLocationChange @1019-1021; FunctionExpression; parameters=0; async=false; generator=false
- onStatusChange @1023-1032; FunctionExpression; parameters=4; async=false; generator=false
- onSecurityChange @1034-1036; FunctionExpression; parameters=0; async=false; generator=false
- onContentBlockingEvent @1038-1040; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1051-1053; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1054-1056; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1060-1069; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1070-1073; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1077-1079; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1080-1083; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1087-1091; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1092-1092; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1096-1100; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1101-1101; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1105-1107; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1108-1110; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1114-1126; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1127-1129; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1133-1135; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1136-1138; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1142-1144; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1145-1149; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1153-1155; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1156-1158; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1162-1164; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1165-1167; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1171-1173; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1174-1176; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1180-1182; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1183-1185; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1189-1191; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1192-1198; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1202-1209; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1210-1212; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1216-1218; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1219-1221; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1225-1227; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1228-1230; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1234-1236; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1237-1239; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1243-1249; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1250-1250; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1254-1256; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1257-1261; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1265-1267; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1268-1270; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1274-1277; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1278-1280; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1284-1289; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1290-1292; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1296-1298; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1299-1301; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1305-1307; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1308-1310; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1314-1316; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1317-1319; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1323-1325; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1326-1339; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1343-1345; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1346-1348; FunctionExpression; parameters=0; async=false; generator=false
- supportsCommand @1352-1354; FunctionExpression; parameters=1; async=false; generator=false
- isCommandEnabled @1356-1361; FunctionExpression; parameters=1; async=false; generator=false
- doCommand @1363-1372; FunctionExpression; parameters=1; async=false; generator=false
- onEvent @1374-1374; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1380-1382; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1383-1385; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1389-1396; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1397-1399; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1403-1405; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1406-1408; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1412-1417; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1418-1420; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1424-1428; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1429-1431; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1435-1440; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1441-1443; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1447-1451; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1452-1454; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1458-1462; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1463-1465; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1469-1473; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1474-1476; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1480-1485; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1486-1488; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1492-1552; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1553-1555; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1559-1578; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1579-1582; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1586-1597; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1598-1600; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1604-1628; FunctionExpression; parameters=0; async=false; generator=false
- doCommand @1629-1640; FunctionExpression; parameters=0; async=false; generator=false
- supportsCommand @1644-1646; FunctionExpression; parameters=1; async=false; generator=false
- isCommandEnabled @1648-1653; FunctionExpression; parameters=1; async=false; generator=false
- doCommand @1655-1664; FunctionExpression; parameters=1; async=false; generator=false
- onEvent @1666-1666; FunctionExpression; parameters=0; async=false; generator=false
- goOpenNewMessage @1674-1692; FunctionDeclaration; parameters=1; async=false; generator=false
- QuoteSelectedMessage @1694-1702; FunctionDeclaration; parameters=0; async=false; generator=false
- GetSelectedMessages @1704-1716; FunctionDeclaration; parameters=0; async=false; generator=false
- SetupCommandUpdateHandlers @1718-1725; FunctionDeclaration; parameters=0; async=false; generator=false
- UnloadCommandUpdateHandlers @1727-1734; FunctionDeclaration; parameters=0; async=false; generator=false
- CommandUpdate_MsgCompose @1736-1746; FunctionDeclaration; parameters=0; async=false; generator=false
- findbarFindReplace @1748-1754; FunctionDeclaration; parameters=0; async=false; generator=false
- updateComposeItems @1756-1787; FunctionDeclaration; parameters=0; async=false; generator=false
- updateAllItems @1795-1836; FunctionDeclaration; parameters=1; async=false; generator=false
- InitFileSaveAsMenu @1838-1848; FunctionDeclaration; parameters=0; async=false; generator=false
- isSmimeSigningConfigured @1850-1852; FunctionDeclaration; parameters=0; async=false; generator=false
- isSmimeEncryptionConfigured @1854-1856; FunctionDeclaration; parameters=0; async=false; generator=false
- isPgpConfigured @1858-1860; FunctionDeclaration; parameters=0; async=false; generator=false
- toggleGlobalSignMessage @1862-1868; FunctionDeclaration; parameters=0; async=false; generator=false
- updateAttachMyPubKey @1870-1878; FunctionDeclaration; parameters=0; async=false; generator=false
- removeAutoDisableNotification @1880-1887; FunctionDeclaration; parameters=0; async=false; generator=false
- toggleEncryptMessage @1889-1898; FunctionDeclaration; parameters=0; async=false; generator=false
- toggleAttachMyPublicKey @1900-1904; FunctionDeclaration; parameters=1; async=false; generator=false
- updateEncryptedSubject @1906-1919; FunctionDeclaration; parameters=0; async=false; generator=false
- toggleEncryptedSubject @1921-1925; FunctionDeclaration; parameters=0; async=false; generator=false
- setSecuritySettings @1932-1991; FunctionDeclaration; parameters=1; async=false; generator=false
- showMessageComposeSecurityStatus @1999-2023; FunctionDeclaration; parameters=1; async=false; generator=false
- msgComposeContextOnShowing @2025-2161; FunctionDeclaration; parameters=1; async=false; generator=false
- msgComposeContextOnHiding @2163-2176; FunctionDeclaration; parameters=1; async=false; generator=false
- updateEditItems @2178-2191; FunctionDeclaration; parameters=0; async=false; generator=false
- updateViewItems @2193-2195; FunctionDeclaration; parameters=0; async=false; generator=false
- updateOptionItems @2197-2200; FunctionDeclaration; parameters=0; async=false; generator=false
- updateAttachmentItems @2202-2216; FunctionDeclaration; parameters=0; async=false; generator=false
- updateReorderAttachmentsItems @2218-2227; FunctionDeclaration; parameters=0; async=false; generator=false
- updateSendCommands @2232-2277; FunctionDeclaration; parameters=1; async=false; generator=false
- addAttachCloudMenuItems @2279-2330; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2315-2315; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addConvertCloudMenuItems @2332-2378; FunctionDeclaration; parameters=3; async=false; generator=false
- updateAttachmentItemProperties @2380-2481; FunctionDeclaration; parameters=1; async=true; generator=false
- showLocalizedCloudFileAlert @2483-2567; FunctionDeclaration; parameters=3; async=true; generator=false
- UpdateAttachment @2588-2848; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @2658-2658; ArrowFunctionExpression; parameters=1; async=false; generator=false
- attachToCloud @2850-2861; FunctionDeclaration; parameters=1; async=false; generator=false
- attachToCloudRepeat @2869-2886; FunctionDeclaration; parameters=2; async=true; generator=false
- attachToCloudNew @2893-2935; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @2912-2912; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2918-2918; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2926-2929; ArrowFunctionExpression; parameters=1; async=false; generator=false
- convertListItemsToCloudAttachment @2944-2963; FunctionDeclaration; parameters=2; async=true; generator=false
- convertSelectedToCloudAttachment @2970-2975; FunctionDeclaration; parameters=1; async=false; generator=false
- convertToCloudAttachment @2983-2993; FunctionDeclaration; parameters=2; async=false; generator=false
- convertListItemsToRegularAttachment @3001-3014; FunctionDeclaration; parameters=1; async=true; generator=false
- convertSelectedToRegularAttachment @3019-3023; FunctionDeclaration; parameters=0; async=false; generator=false
- observe @3031-3048; FunctionExpression; parameters=2; async=false; generator=false
- AddMessageComposeOfflineQuitObserver @3051-3063; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveMessageComposeOfflineQuitObserver @3065-3074; FunctionDeclaration; parameters=0; async=false; generator=false
- MessageComposeOfflineStateChanged @3082-3096; FunctionDeclaration; parameters=1; async=false; generator=false
- DoCommandPrint @3098-3107; FunctionDeclaration; parameters=0; async=false; generator=false
- editorBrowser.onFirstPrintDialogOpened @3100-3100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- editorBrowser.onLastPrintDialogClosed @3101-3101; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ToggleWindowLock @3116-3129; FunctionDeclaration; parameters=1; async=false; generator=false
- GetArgs @3132-3205; FunctionDeclaration; parameters=1; async=false; generator=false
- ComposeFieldsReady @3207-3229; FunctionDeclaration; parameters=0; async=false; generator=false
- observeRecipientsChange @3234-3265; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @3238-3242; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3239-3239; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callCheckEncryptionState @3250-3253; FunctionDeclaration; parameters=0; async=false; generator=false
- handleEsc @3272-3296; FunctionDeclaration; parameters=0; async=false; generator=false
- manageAttachmentNotification @3319-3452; FunctionDeclaration; parameters=1; async=false; generator=false
- msg.onclick @3377-3381; FunctionExpression; parameters=0; async=false; generator=false
- callback @3400-3403; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3414-3418; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3428-3430; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3442-3451; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3448-3450; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clearRecipPillKeyIssues @3454-3458; FunctionDeclaration; parameters=0; async=false; generator=false
- getEncryptionCompatibleRecipients @3463-3473; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @3470-3470; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mustCheckRecipientKeys @3481-3494; FunctionDeclaration; parameters=0; async=false; generator=false
- checkRecipientKeys @3507-3523; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @3518-3518; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mustCheckRecipientCerts @3528-3542; FunctionDeclaration; parameters=0; async=false; generator=false
- checkRecipientCerts @3558-3660; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @3559-3659; ArrowFunctionExpression; parameters=2; async=false; generator=false
- continueCheckRecipientCerts @3570-3575; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @3572-3572; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findCertDone @3583-3639; FunctionExpression; parameters=2; async=false; generator=false
- checkEncryptionState @3724-3932; FunctionDeclaration; parameters=1; async=true; generator=false
- continueCheckEncryptionStateSub @3771-3916; FunctionDeclaration; parameters=0; async=true; generator=false
- updateEncryptionTechReminder @3941-3976; FunctionDeclaration; parameters=1; async=true; generator=false
- callback @3966-3972; FunctionExpression; parameters=0; async=false; generator=false
- notifyIdentityCannotEncrypt @3986-4011; FunctionDeclaration; parameters=2; async=true; generator=false
- updateKeyCertNotifications @4023-4105; FunctionDeclaration; parameters=1; async=true; generator=false
- callback @4056-4061; FunctionExpression; parameters=0; async=false; generator=false
- callback @4067-4070; FunctionExpression; parameters=0; async=false; generator=false
- attachmentNotificationSupressed @4113-4119; FunctionDeclaration; parameters=0; async=false; generator=false
- attachmentWorker.onerror @4129-4131; FunctionExpression; parameters=1; async=false; generator=false
- attachmentWorker.onmessage @4139-4149; FunctionExpression; parameters=1; async=false; generator=false
- attachmentWorker.findAttachmentKeywords @4158-4168; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @4159-4168; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4162-4164; ArrowFunctionExpression; parameters=1; async=false; generator=false
- AttachmentsChanged @4181-4186; FunctionDeclaration; parameters=2; async=false; generator=false
- getValidSpellcheckerDictionaries @4208-4239; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4226-4226; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4232-4232; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observe @4242-4270; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @4252-4252; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4257-4257; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addObserver @4274-4277; FunctionExpression; parameters=0; async=false; generator=false
- removeObserver @4279-4284; FunctionExpression; parameters=0; async=false; generator=false
- EditorClick @4287-4327; FunctionDeclaration; parameters=1; async=false; generator=false
- ?.onclick @4307-4309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.onclick @4310-4313; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.onclick @4314-4319; ArrowFunctionExpression; parameters=1; async=false; generator=false
- settings.onkeydown @4321-4325; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addLinkPreview @4335-4459; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @4337-4337; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4338-4458; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onPasteOrDrop @4465-4584; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4479-4480; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4543-4582; FunctionExpression; parameters=1; async=false; generator=false
- doTheInsert @4550-4561; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4565-4572; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4573-4578; FunctionExpression; parameters=0; async=false; generator=false
- ComposeStartup @4587-5275; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @5099-5112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5164-5164; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5243-5251; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5252-5254; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5255-5257; ArrowFunctionExpression; parameters=0; async=false; generator=false
- splitEmailAddress @5278-5281; FunctionDeclaration; parameters=1; async=false; generator=false
- emailSimilar @5284-5291; FunctionDeclaration; parameters=2; async=false; generator=false
- observe @5295-5310; FunctionExpression; parameters=2; async=false; generator=false
- adjustEncryptAfterIdentityChange @5320-5472; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @5328-5328; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5330-5331; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5333-5334; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ComposeLoad @5474-5675; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @5479-5479; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5517-5518; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5520-5521; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5523-5524; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5529-5546; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5555-5555; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toolbox.customizeDone @5600-5602; FunctionExpression; parameters=1; async=false; generator=false
- input.onBeforeHandleKeyDown @5608-5609; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5646-5648; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setComposeLabelsAndMenuItems @5680-5740; FunctionDeclaration; parameters=0; async=false; generator=false
- setKeyboardShortcuts @5745-5808; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @5751-5794; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5796-5807; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ComposeUnload @5810-5864; FunctionDeclaration; parameters=0; async=false; generator=false
- onEncryptionChoice @5866-5902; FunctionDeclaration; parameters=1; async=false; generator=false
- supportsCommand @5905-5913; FunctionExpression; parameters=1; async=false; generator=false
- isCommandEnabled @5915-5923; FunctionExpression; parameters=1; async=false; generator=false
- updateEncryptOptionsMenuElements @5926-5948; FunctionDeclaration; parameters=0; async=false; generator=false
- updateAriaLabelsAndTooltipsOfAllAddressRows @5955-5962; FunctionDeclaration; parameters=0; async=true; generator=false
- updateAriaLabelsOfAddressRow @5971-5998; FunctionDeclaration; parameters=1; async=true; generator=false
- updateTooltipsOfAddressRow @6005-6009; FunctionDeclaration; parameters=1; async=false; generator=false
- onSendSMIME @6016-6061; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @6031-6031; ArrowFunctionExpression; parameters=1; async=false; generator=false
- DoSpellCheckBeforeSend @6064-6066; FunctionDeclaration; parameters=0; async=false; generator=false
- GetComposeDetails @6073-6087; FunctionDeclaration; parameters=0; async=false; generator=false
- SetComposeDetails @6104-6154; FunctionDeclaration; parameters=1; async=false; generator=false
- GenericSendMessage @6161-6463; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @6185-6197; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6230-6231; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6234-6238; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6372-6376; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6373-6373; ArrowFunctionExpression; parameters=1; async=false; generator=false
- CompleteGenericSendMessage @6472-6630; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @6607-6607; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isValidAddress @6637-6639; FunctionDeclaration; parameters=1; async=false; generator=false
- isValidNewsAddress @6646-6648; FunctionDeclaration; parameters=1; async=false; generator=false
- focusAddressInputOnClick @6656-6661; FunctionDeclaration; parameters=1; async=false; generator=false
- updateSendLock @6666-6738; FunctionDeclaration; parameters=0; async=false; generator=false
- CheckValidEmailAddress @6746-6790; FunctionDeclaration; parameters=1; async=true; generator=false
- pillifyRecipients @6800-6814; FunctionDeclaration; parameters=0; async=true; generator=false
- showAddressRowButtonOnDragover @6821-6825; FunctionDeclaration; parameters=1; async=false; generator=false
- showAddressRowButtonOnDrop @6832-6861; FunctionDeclaration; parameters=1; async=false; generator=false
- cutSelectedPillsOnCommand @6866-6868; FunctionDeclaration; parameters=0; async=false; generator=false
- copySelectedPillsOnCommand @6873-6875; FunctionDeclaration; parameters=0; async=false; generator=false
- selectAllSiblingPillsOnCommand @6883-6891; FunctionDeclaration; parameters=1; async=false; generator=false
- selectAllPillsOnCommand @6896-6898; FunctionDeclaration; parameters=0; async=false; generator=false
- deleteSelectedPillsOnCommand @6903-6905; FunctionDeclaration; parameters=0; async=false; generator=false
- moveSelectedPillsOnCommand @6912-6916; FunctionDeclaration; parameters=1; async=false; generator=false
- checkPublicRecipientsLimit @6921-7038; FunctionDeclaration; parameters=0; async=false; generator=false
- callback @6961-6975; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6964-6964; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callback @6980-7002; FunctionExpression; parameters=0; async=false; generator=false
- eventCallback @7014-7018; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7022-7037; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getPublicAddressPills @7045-7050; FunctionDeclaration; parameters=0; async=false; generator=false
- getPublicAddressPillsCount @7056-7063; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @7059-7060; ArrowFunctionExpression; parameters=2; async=false; generator=false
- checkEncryptedBccRecipients @7069-7120; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @7085-7085; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callback @7101-7104; FunctionExpression; parameters=0; async=false; generator=false
- eventCallback @7112-7116; FunctionExpression; parameters=1; async=false; generator=false
- SendMessage @7122-7140; FunctionDeclaration; parameters=0; async=true; generator=false
- SendMessageWithCheck @7142-7189; FunctionDeclaration; parameters=0; async=true; generator=false
- SendMessageLater @7191-7195; FunctionDeclaration; parameters=0; async=true; generator=false
- ExitFullscreenMode @7197-7202; FunctionDeclaration; parameters=0; async=false; generator=false
- Save @7204-7216; FunctionDeclaration; parameters=0; async=false; generator=false
- SaveAsFile @7218-7228; FunctionDeclaration; parameters=1; async=false; generator=false
- SaveAsDraft @7230-7237; FunctionDeclaration; parameters=0; async=true; generator=false
- SaveAsTemplate @7239-7261; FunctionDeclaration; parameters=0; async=true; generator=false
- MessageFcc @7264-7277; FunctionDeclaration; parameters=1; async=false; generator=false
- updateOptionsMenu @7279-7284; FunctionDeclaration; parameters=0; async=false; generator=false
- updatePriorityMenu @7286-7297; FunctionDeclaration; parameters=0; async=false; generator=false
- updatePriorityToolbarButton @7299-7304; FunctionDeclaration; parameters=1; async=false; generator=false
- PriorityMenuSelect @7306-7316; FunctionDeclaration; parameters=1; async=false; generator=false
- initSendFormatMenu @7321-7361; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @7355-7360; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addRecipientsToIgnoreList @7370-7400; FunctionDeclaration; parameters=1; async=false; generator=false
- observe @7411-7418; FunctionExpression; parameters=2; async=false; generator=false
- addObserver @7422-7429; FunctionExpression; parameters=0; async=false; generator=false
- removeObserver @7431-7439; FunctionExpression; parameters=0; async=false; generator=false
- addWordsToIgnore @7441-7450; FunctionExpression; parameters=1; async=false; generator=false
- _addWords @7452-7461; FunctionExpression; parameters=0; async=false; generator=false
- _clearPendingWords @7463-7465; FunctionExpression; parameters=0; async=false; generator=false
- onRecipientsChanged @7475-7480; FunctionDeclaration; parameters=1; async=false; generator=false
- showPopupById @7504-7525; FunctionDeclaration; parameters=8; async=false; generator=false
- InitLanguageMenu @7527-7578; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @7553-7556; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7565-7575; ArrowFunctionExpression; parameters=1; async=false; generator=false
- OnShowDictionaryMenu @7580-7589; FunctionDeclaration; parameters=1; async=false; generator=false
- languageMenuListOpened @7591-7595; FunctionDeclaration; parameters=0; async=false; generator=false
- languageMenuListClosed @7597-7601; FunctionDeclaration; parameters=0; async=false; generator=false
- ComposeChangeLanguage @7619-7693; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @7637-7644; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observe @7638-7643; FunctionExpression; parameters=2; async=false; generator=false
- ChangeLanguage @7702-7711; FunctionDeclaration; parameters=1; async=false; generator=false
- updateLanguageInStatusBar @7718-7766; FunctionDeclaration; parameters=1; async=true; generator=false
- ToggleReturnReceipt @7774-7792; FunctionDeclaration; parameters=1; async=false; generator=false
- ToggleDSN @7794-7801; FunctionDeclaration; parameters=1; async=false; generator=false
- ToggleAttachVCard @7803-7810; FunctionDeclaration; parameters=1; async=false; generator=false
- toggleAttachmentReminder @7823-7834; FunctionDeclaration; parameters=1; async=false; generator=false
- toggleAttachmentAnimation @7840-7842; FunctionDeclaration; parameters=0; async=false; generator=false
- FillIdentityList @7844-7907; FunctionDeclaration; parameters=1; async=false; generator=false
- getCurrentAccountKey @7909-7913; FunctionDeclaration; parameters=0; async=false; generator=false
- getCurrentIdentityKey @7915-7918; FunctionDeclaration; parameters=0; async=false; generator=false
- AdjustFocus @7920-7945; FunctionDeclaration; parameters=0; async=false; generator=false
- SetComposeWindowTitle @7950-7964; FunctionDeclaration; parameters=0; async=false; generator=false
- ComposeCanClose @7972-8095; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveDraft @8097-8123; FunctionDeclaration; parameters=0; async=false; generator=false
- SetContentAndBodyAsUnmodified @8125-8128; FunctionDeclaration; parameters=0; async=false; generator=false
- GetLastAttachDirectory @8130-8145; FunctionDeclaration; parameters=0; async=false; generator=false
- SetLastAttachDirectory @8150-8163; FunctionDeclaration; parameters=1; async=false; generator=false
- AttachFile @8165-8201; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @8186-8200; ArrowFunctionExpression; parameters=1; async=false; generator=false
- FileToAttachment @8209-8220; FunctionDeclaration; parameters=1; async=false; generator=false
- messageAttachmentToFile @8222-8282; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @8240-8276; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onDataAvailable @8244-8252; FunctionExpression; parameters=4; async=false; generator=false
- onStartRequest @8253-8253; FunctionExpression; parameters=0; async=false; generator=false
- onStopRequest @8254-8261; FunctionExpression; parameters=2; async=false; generator=false
- AddAttachments @8292-8448; FunctionDeclaration; parameters=2; async=true; generator=false
- attachmentsGetSortedArray @8461-8499; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8486-8488; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @8493-8495; ArrowFunctionExpression; parameters=2; async=false; generator=false
- attachmentsSelectionGetSortedArray @8509-8511; FunctionDeclaration; parameters=1; async=false; generator=false
- attachmentsSelectionIsBlock @8528-8556; FunctionDeclaration; parameters=1; async=false; generator=false
- AttachPage @8558-8582; FunctionDeclaration; parameters=0; async=false; generator=false
- DuplicateFileAlreadyAttached @8590-8608; FunctionDeclaration; parameters=1; async=false; generator=false
- Attachments2CompFields @8610-8619; FunctionDeclaration; parameters=1; async=false; generator=false
- RemoveAllAttachments @8621-8627; FunctionDeclaration; parameters=0; async=true; generator=false
- updateAttachmentPane @8638-8673; FunctionDeclaration; parameters=1; async=false; generator=false
- RemoveSelectedAttachment @8675-8677; FunctionDeclaration; parameters=0; async=true; generator=false
- RemoveAttachments @8689-8757; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @8711-8711; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8717-8717; ArrowFunctionExpression; parameters=1; async=false; generator=false
- RenameSelectedAttachment @8759-8791; FunctionDeclaration; parameters=0; async=true; generator=false
- moveSelectedAttachments @8805-9041; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @9005-9006; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @9010-9011; ArrowFunctionExpression; parameters=2; async=false; generator=false
- toggleAttachmentPane @9051-9073; FunctionDeclaration; parameters=1; async=false; generator=false
- attachmentAreaOnToggle @9078-9106; FunctionDeclaration; parameters=0; async=false; generator=false
- moveFocusToAttachmentPane @9112-9118; FunctionDeclaration; parameters=0; async=false; generator=false
- showReorderAttachmentsPanel @9120-9138; FunctionDeclaration; parameters=0; async=false; generator=false
- attachmentsSelectionGetSortOrder @9152-9154; FunctionDeclaration; parameters=0; async=false; generator=false
- attachmentsGetSortOrder @9171-9221; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @9193-9195; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @9200-9202; ArrowFunctionExpression; parameters=2; async=false; generator=false
- reorderAttachmentsPanelOnPopupShowing @9223-9240; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @9228-9232; ArrowFunctionExpression; parameters=1; async=false; generator=false
- attachmentBucketOnBlur @9246-9260; FunctionDeclaration; parameters=0; async=false; generator=false
- attachmentBucketOnKeyPress @9267-9340; FunctionDeclaration; parameters=1; async=false; generator=false
- attachmentBucketOnClick @9342-9352; FunctionDeclaration; parameters=1; async=false; generator=false
- attachmentBucketOnSelect @9354-9357; FunctionDeclaration; parameters=0; async=false; generator=false
- attachmentBucketUpdateTooltips @9359-9370; FunctionDeclaration; parameters=0; async=false; generator=false
- OpenSelectedAttachment @9372-9436; FunctionDeclaration; parameters=0; async=false; generator=false
- nsAttachmentOpener @9438-9438; FunctionDeclaration; parameters=0; async=false; generator=false
- doContent @9447-9458; FunctionExpression; parameters=3; async=false; generator=false
- isPreferred @9460-9465; FunctionExpression; parameters=1; async=false; generator=false
- canHandleContent @9467-9469; FunctionExpression; parameters=0; async=false; generator=false
- getInterface @9471-9479; FunctionExpression; parameters=1; async=false; generator=false
- determineSendFormat @9492-9512; FunctionDeclaration; parameters=0; async=false; generator=false
- expandRecipients @9517-9519; FunctionDeclaration; parameters=0; async=false; generator=false
- hideIrrelevantAddressingOptions @9530-9556; FunctionDeclaration; parameters=2; async=false; generator=false
- LoadIdentity @9558-9803; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @9696-9696; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9720-9720; ArrowFunctionExpression; parameters=1; async=false; generator=false
- MakeFromFieldEditable @9805-9850; FunctionDeclaration; parameters=1; async=false; generator=false
- fromKeyPress @9857-9866; FunctionDeclaration; parameters=1; async=false; generator=false
- subjectKeyPress @9873-9888; FunctionDeclaration; parameters=1; async=false; generator=false
- msgIdentityOnInput @9895-9897; FunctionDeclaration; parameters=1; async=false; generator=false
- msgSubjectOnInput @9904-9908; FunctionDeclaration; parameters=1; async=false; generator=false
- _adjustDropTarget @9933-10006; FunctionExpression; parameters=1; async=false; generator=false
- _showDropMarker @10008-10018; FunctionExpression; parameters=1; async=false; generator=false
- _hideDropMarker @10020-10024; FunctionExpression; parameters=0; async=false; generator=false
- getValidAttachments @10034-10166; FunctionExpression; parameters=1; async=false; generator=false
- _reorderDraggedAttachments @10173-10243; FunctionExpression; parameters=1; async=false; generator=false
- handleInlineDrop @10245-10269; FunctionExpression; parameters=1; async=false; generator=false
- onDrop @10271-10365; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @10292-10292; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDragOver @10367-10463; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10411-10411; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDragLeave @10465-10484; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10472-10481; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _hideDropOverlay @10491-10497; FunctionExpression; parameters=0; async=false; generator=false
- isNotDraggingOnlyImages @10507-10514; FunctionExpression; parameters=1; async=false; generator=false
- detectHoveredOverlay @10522-10529; FunctionExpression; parameters=1; async=false; generator=false
- appendImagesInline @10538-10580; FunctionExpression; parameters=1; async=false; generator=false
- onDragStart @10585-10599; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10594-10594; ArrowFunctionExpression; parameters=1; async=false; generator=false
- DisplaySaveFolderDlg @10602-10637; FunctionDeclaration; parameters=1; async=false; generator=false
- focusContactsSidebarSearchInput @10646-10658; FunctionDeclaration; parameters=0; async=false; generator=false
- focusMsgIdentity @10667-10670; FunctionDeclaration; parameters=0; async=false; generator=false
- focusAddressRowInput @10681-10687; FunctionDeclaration; parameters=1; async=false; generator=false
- focusSubjectInput @10696-10699; FunctionDeclaration; parameters=0; async=false; generator=false
- focusMsgBody @10708-10714; FunctionDeclaration; parameters=0; async=false; generator=false
- focusAttachmentBucket @10725-10740; FunctionDeclaration; parameters=1; async=false; generator=false
- focusNotification @10749-10762; FunctionDeclaration; parameters=0; async=false; generator=false
- focusStatusBar @10772-10779; FunctionDeclaration; parameters=1; async=false; generator=false
- moveFocusToNeighbouringArea @10787-10827; FunctionDeclaration; parameters=1; async=false; generator=false
- toggleContactsSidebar @10833-10838; FunctionDeclaration; parameters=0; async=false; generator=false
- setContactsSidebarVisibility @10847-10899; FunctionDeclaration; parameters=2; async=false; generator=false
- loadHTMLMsgPrefs @10901-10935; FunctionDeclaration; parameters=0; async=false; generator=false
- AutoSave @10937-10953; FunctionDeclaration; parameters=0; async=true; generator=false
- init @10963-11000; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10975-10982; FunctionExpression; parameters=0; async=false; generator=false
- subjectInputObserver @11004-11011; FunctionExpression; parameters=0; async=false; generator=false
- checkForAttachmentKeywords @11018-11123; FunctionExpression; parameters=0; async=true; generator=false
- shutdown @11125-11132; FunctionExpression; parameters=0; async=false; generator=false
- notify @11135-11142; FunctionExpression; parameters=0; async=true; generator=false
- removeQueryPart @11156-11174; FunctionDeclaration; parameters=2; async=false; generator=false
- InitEditor @11176-11405; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @11228-11299; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11400-11400; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setFontSize @11407-11415; FunctionDeclaration; parameters=1; async=false; generator=false
- setParagraphState @11417-11419; FunctionDeclaration; parameters=1; async=false; generator=false
- updateDocumentLanguage @11423-11425; FunctionDeclaration; parameters=1; async=false; generator=false
- toggleSpellCheckingEnabled @11427-11429; FunctionDeclaration; parameters=0; async=false; generator=false
- enableInlineSpellCheck @11434-11448; FunctionDeclaration; parameters=1; async=false; generator=false
- UpdateFullZoomMenu @11451-11454; FunctionDeclaration; parameters=0; async=false; generator=false
- getBrowser @11461-11463; FunctionDeclaration; parameters=0; async=false; generator=false
- goUpdateMailMenuItems @11465-11472; FunctionDeclaration; parameters=1; async=false; generator=false
- brandBundle @11479-11482; FunctionExpression; parameters=0; async=false; generator=false
- setBlockedContent @11484-11533; FunctionExpression; parameters=1; async=true; generator=false
- callback @11499-11501; FunctionExpression; parameters=0; async=false; generator=false
- isShowingBlockedContentNotification @11535-11537; FunctionExpression; parameters=0; async=false; generator=false
- clearBlockedContentNotification @11539-11543; FunctionExpression; parameters=0; async=false; generator=false
- clearNotifications @11545-11547; FunctionExpression; parameters=0; async=false; generator=false
- setIdentityWarning @11556-11577; FunctionExpression; parameters=1; async=true; generator=false
- clearIdentityWarning @11579-11585; FunctionExpression; parameters=0; async=false; generator=false
- onBlockedContentOptionsShowing @11591-11611; FunctionDeclaration; parameters=1; async=false; generator=false
- onUnblockResource @11620-11646; FunctionDeclaration; parameters=2; async=false; generator=false
- showSendEncryptedAndSigned @11651-11671; FunctionDeclaration; parameters=0; async=false; generator=false
- updateEncryptionDependencies @11677-11725; FunctionDeclaration; parameters=0; async=false; generator=false
- composeWindowOnClick @11732-11754; FunctionDeclaration; parameters=1; async=false; generator=false
- Module resource:///modules/activity/activityModules.sys.mjs @42; ChromeUtils-import-literal
- Module resource:///modules/cloudFileAccounts.sys.mjs @45; ChromeUtils-import-literal
- Module resource:///modules/mimeParser.sys.mjs @48; ChromeUtils-import-literal
- Module resource:///modules/MailServices.sys.mjs @51; ChromeUtils-import-literal
- Module resource://gre/modules/AppConstants.sys.mjs @54; ChromeUtils-import-literal
- Module resource://gre/modules/ExtensionParent.sys.mjs @57; ChromeUtils-import-literal
- Module chrome://openpgp/content/modules/funcs.sys.mjs @60; ChromeUtils-import-literal
- Module resource:///modules/TaskbarProgress.sys.mjs @118; ChromeUtils-import-literal

### mail/components/compose/content/addressingWidgetOverlay.js

Blob: `f7e1820aee4d2a236deae6c6bca7a4e4176b12a7`. Role: source. Parse: module.

- Recipients2CompFields @29-78; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRecipientList @59-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @64-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setAddressRowFromCompField @92-113; FunctionDeclaration; parameters=4; async=false; generator=false
- CompFields2Recipients @121-178; FunctionDeclaration; parameters=1; async=false; generator=false
- updateUIforNNTPAccount @184-218; FunctionDeclaration; parameters=0; async=false; generator=false
- updateUIforMailAccount @225-254; FunctionDeclaration; parameters=0; async=false; generator=false
- awRemoveRecipients @268-314; FunctionDeclaration; parameters=3; async=false; generator=false
- awAddRecipients @324-335; FunctionDeclaration; parameters=3; async=false; generator=false
- addressRowAddRecipientsArray @346-376; FunctionDeclaration; parameters=3; async=false; generator=false
- DropRecipient @384-398; FunctionDeclaration; parameters=2; async=false; generator=false
- getLoadContext @405-407; FunctionDeclaration; parameters=0; async=false; generator=false
- focusNextAddressRow @415-424; FunctionDeclaration; parameters=1; async=false; generator=false
- otherHeaderInputOnKeyDown @433-499; FunctionDeclaration; parameters=1; async=false; generator=false
- addressInputOnBeforeHandleKeyDown @508-783; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @766-768; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addressInputOnInput @792-829; FunctionDeclaration; parameters=2; async=false; generator=false
- recipientAddPills @840-894; FunctionDeclaration; parameters=2; async=false; generator=false
- addressRowClearPills @901-908; FunctionDeclaration; parameters=1; async=false; generator=false
- addressInputOnFocus @916-918; FunctionDeclaration; parameters=1; async=false; generator=false
- addressInputOnBlur @926-982; FunctionDeclaration; parameters=1; async=false; generator=false
- editAddressPill @991-995; FunctionDeclaration; parameters=2; async=false; generator=false
- expandList @1003-1025; FunctionDeclaration; parameters=1; async=false; generator=false
- onPillPopupShowing @1033-1123; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1069-1069; ArrowFunctionExpression; parameters=1; async=false; generator=false
- showAndFocusAddressRow @1131-1136; FunctionDeclaration; parameters=1; async=false; generator=false
- addressRowSetVisibility @1146-1156; FunctionDeclaration; parameters=2; async=false; generator=false
- showAddressRowMenuItemSetVisibility @1164-1179; FunctionDeclaration; parameters=2; async=false; generator=false
- showAddressRowMenuItemSetPreferButton @1190-1207; FunctionDeclaration; parameters=2; async=false; generator=false
- updateRecipientsVisibility @1213-1224; FunctionDeclaration; parameters=0; async=false; generator=false
- hideAddressRowFromWithin @1238-1325; FunctionDeclaration; parameters=2; async=true; generator=false
- closeLabelOnClick @1332-1334; FunctionDeclaration; parameters=1; async=false; generator=false
- extraAddressRowsMenuOpened @1336-1340; FunctionDeclaration; parameters=0; async=false; generator=false
- extraAddressRowsMenuClosed @1342-1346; FunctionDeclaration; parameters=0; async=false; generator=false
- openExtraAddressRowsMenu @1351-1356; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource:///modules/mimeParser.sys.mjs @9; ChromeUtils-import-literal
- Module resource:///modules/DisplayNameUtils.sys.mjs @12; ChromeUtils-import-literal

### mail/components/compose/content/bigFileObserver.js

Blob: `852fc72ef27333af018a185e7335d21805e9ac06`. Role: source. Parse: module.

- hidden @20-27; FunctionExpression; parameters=0; async=false; generator=false
- hide @29-35; FunctionExpression; parameters=1; async=false; generator=false
- init @37-49; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @51-88; FunctionExpression; parameters=1; async=false; generator=false
- bigFileTrackerAdd @90-100; FunctionExpression; parameters=1; async=false; generator=false
- bigFileTrackerRemove @102-109; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateBigFileNotification @112-181; FunctionExpression; parameters=0; async=true; generator=false
- callback @139-148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-145; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callback @152-161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @154-158; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openLearnMore @183-187; FunctionExpression; parameters=0; async=false; generator=false
- convertAttachments @189-240; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @202-202; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @203-203; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hideBigFileNotification @242-256; FunctionExpression; parameters=0; async=true; generator=false
- updateUploadingNotification @259-334; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @292-294; FunctionExpression; parameters=0; async=false; generator=false
- callback @312-317; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @331-333; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hidePrivacyNotification @336-345; FunctionExpression; parameters=0; async=false; generator=false
- checkAndHidePrivacyNotification @347-355; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @350-350; ArrowFunctionExpression; parameters=1; async=false; generator=false
- showPrivacyNotification @357-381; FunctionExpression; parameters=0; async=true; generator=false
- uploadsInProgress @383-386; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @385-385; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource:///modules/cloudFileAccounts.sys.mjs @8; ChromeUtils-import-literal
- Module resource://gre/modules/PromptUtils.sys.mjs @198; ChromeUtils-import-literal

### mail/components/compose/content/cloudAttachmentLinkManager.js

Blob: `b147da97b797a14687384703bec676e6274936cc`. Role: source. Parse: module.

- init @16-37; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeFieldsReady @39-39; FunctionExpression; parameters=0; async=false; generator=false
- NotifyComposeBodyReady @40-40; FunctionExpression; parameters=0; async=false; generator=false
- ComposeProcessDone @41-41; FunctionExpression; parameters=0; async=false; generator=false
- SaveInFolderDone @42-42; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @44-117; FunctionExpression; parameters=1; async=true; generator=false
- _removeRoot @124-129; FunctionExpression; parameters=1; async=false; generator=false
- _getHTMLRepresentation @138-142; FunctionExpression; parameters=2; async=false; generator=false
- _getTextRepresentation @150-152; FunctionExpression; parameters=1; async=false; generator=false
- _generateLink @163-169; FunctionExpression; parameters=4; async=false; generator=false
- _findInsertionPoint @171-288; FunctionExpression; parameters=1; async=false; generator=false
- _resetNodeIDs @297-304; FunctionExpression; parameters=2; async=false; generator=false
- _insertHeader @312-396; FunctionExpression; parameters=1; async=false; generator=false
- _updateAttachmentCount @404-420; FunctionExpression; parameters=1; async=true; generator=false
- _updateServiceProviderLinks @427-480; FunctionExpression; parameters=1; async=true; generator=false
- _insertItem @489-499; FunctionExpression; parameters=2; async=true; generator=false
- _createNode @525-735; FunctionExpression; parameters=3; async=true; generator=false
- statsRow @561-584; ArrowFunctionExpression; parameters=3; async=false; generator=false
- serviceRow @657-675; ArrowFunctionExpression; parameters=0; async=false; generator=false
- send @745-768; FunctionExpression; parameters=1; async=false; generator=false
- Module resource:///modules/MimeMessageUtils.sys.mjs @7; ChromeUtils-import-literal
- Module resource:///modules/ComposeUtils.sys.mjs @11; ChromeUtils-import-literal

### mail/components/compose/content/composeWidgets.mjs

Blob: `94b0f752842df4758f6750004d7245cda5b0b6eb`. Role: source. Parse: module.

- inheritedAttributes @31-35; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @59-114; FunctionExpression; parameters=0; async=false; generator=false
- observe @95-99; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @109-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- emailAddress @116-118; FunctionExpression; parameters=0; async=false; generator=false
- emailAddress @120-122; FunctionExpression; parameters=1; async=false; generator=false
- label @124-126; FunctionExpression; parameters=0; async=false; generator=false
- label @128-130; FunctionExpression; parameters=1; async=false; generator=false
- fullAddress @132-134; FunctionExpression; parameters=0; async=false; generator=false
- fullAddress @136-138; FunctionExpression; parameters=1; async=false; generator=false
- displayName @140-142; FunctionExpression; parameters=0; async=false; generator=false
- displayName @144-146; FunctionExpression; parameters=1; async=false; generator=false
- emailInput @148-150; FunctionExpression; parameters=0; async=false; generator=false
- rowInput @155-159; FunctionExpression; parameters=0; async=false; generator=false
- isEditing @167-169; FunctionExpression; parameters=0; async=false; generator=false
- fragment @171-191; FunctionExpression; parameters=0; async=false; generator=false
- _setupEmailInput @193-196; FunctionExpression; parameters=0; async=false; generator=false
- _setupEventListeners @198-245; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @199-212; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @214-219; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @224-244; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isValidAddress @253-255; FunctionExpression; parameters=1; async=false; generator=false
- startEditing @261-287; FunctionExpression; parameters=0; async=false; generator=false
- onEmailInputKeyPress @295-309; FunctionExpression; parameters=1; async=false; generator=false
- updatePill @311-365; FunctionExpression; parameters=0; async=true; generator=false
- resetPill @367-377; FunctionExpression; parameters=0; async=false; generator=false
- updatePillStatus @383-438; FunctionExpression; parameters=0; async=true; generator=false
- getUnselectedSiblingPill @447-471; FunctionExpression; parameters=1; async=false; generator=false
- removeObserver @473-478; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @490-665; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @502-509; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @511-513; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @520-533; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @535-561; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @553-553; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @563-565; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @567-586; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @588-603; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @605-664; ArrowFunctionExpression; parameters=1; async=false; generator=false
- resizeInputField @675-690; FunctionExpression; parameters=2; async=false; generator=false
- createDNDPills @709-776; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @718-718; ArrowFunctionExpression; parameters=1; async=false; generator=false
- buildRecipientRow @789-915; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @811-813; ArrowFunctionExpression; parameters=1; async=false; generator=false
- input.onBeforeHandleKeyDown @878-880; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @886-888; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @891-893; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @894-896; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @908-909; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupAutocompleteInput @922-939; FunctionExpression; parameters=1; async=false; generator=false
- input.openPopup @931-938; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createRecipientPill @950-1044; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @958-995; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @997-1002; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1004-1009; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleKeyDown @1052-1072; FunctionExpression; parameters=2; async=false; generator=false
- handleKeyPress @1080-1203; FunctionExpression; parameters=2; async=false; generator=false
- checkSelected @1212-1230; FunctionExpression; parameters=2; async=false; generator=false
- checkKeyboardSelected @1240-1273; FunctionExpression; parameters=2; async=false; generator=false
- startEditing @1281-1288; FunctionExpression; parameters=2; async=false; generator=false
- copySelectedPills @1293-1302; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1296-1296; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cutSelectedPills @1307-1310; FunctionExpression; parameters=0; async=false; generator=false
- moveSelectedPills @1317-1338; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1320-1320; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeSelectedPills @1351-1419; FunctionExpression; parameters=3; async=false; generator=false
- selectSiblingPills @1427-1431; FunctionExpression; parameters=1; async=false; generator=false
- selectAllPills @1436-1440; FunctionExpression; parameters=0; async=false; generator=false
- deselectAllPills @1445-1449; FunctionExpression; parameters=0; async=false; generator=false
- getSiblingPills @1458-1462; FunctionExpression; parameters=1; async=false; generator=false
- getAllPills @1469-1471; FunctionExpression; parameters=0; async=false; generator=false
- getAllSelectedPills @1478-1480; FunctionExpression; parameters=0; async=false; generator=false
- hasSelectedPills @1487-1489; FunctionExpression; parameters=0; async=false; generator=false
- moveFocusToPreviousElement @1496-1525; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1532-1535; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1535-1535; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MailRecipientsArea @489-1526
- Class MailAddressPill @30-479
- Module resource:///modules/MailServices.sys.mjs @16; ChromeUtils-import-literal

### mail/components/compose/content/dialogs/EdAEAttributes.js

Blob: `52b7e30faca299eaeb2ed70500a5f71e7a3e4c77`. Role: source. Parse: module.


### mail/components/compose/content/dialogs/EdAECSSAttributes.js

Blob: `086f2f01d74a2456e1b860030996b8385627b342`. Role: source. Parse: module.

- BuildCSSAttributeTable @9-35; FunctionDeclaration; parameters=0; async=false; generator=false
- onChangeCSSAttribute @37-50; FunctionDeclaration; parameters=0; async=false; generator=false
- ClearCSSInputWidgets @52-57; FunctionDeclaration; parameters=0; async=false; generator=false
- onSelectCSSTreeItem @59-73; FunctionDeclaration; parameters=0; async=false; generator=false
- onInputCSSAttributeName @75-87; FunctionDeclaration; parameters=0; async=false; generator=false
- editCSSAttributeValue @89-93; FunctionDeclaration; parameters=1; async=false; generator=false
- UpdateCSSAttributes @95-125; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveCSSAttribute @127-137; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectCSSTree @139-145; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdAEHTMLAttributes.js

Blob: `eedfea37c4bd4908d002c78b95e4ecffcd30edd7`. Role: source. Parse: module.

- BuildHTMLAttributeNameList @8-84; FunctionDeclaration; parameters=0; async=false; generator=false
- BuildHTMLAttributeTable @87-113; FunctionDeclaration; parameters=0; async=false; generator=false
- ClearHTMLInputWidgets @115-120; FunctionDeclaration; parameters=0; async=false; generator=false
- onSelectHTMLTreeItem @122-147; FunctionDeclaration; parameters=0; async=false; generator=false
- onInputHTMLAttributeName @149-240; FunctionDeclaration; parameters=0; async=false; generator=false
- onInputHTMLAttributeValue @242-308; FunctionDeclaration; parameters=0; async=false; generator=false
- editHTMLAttributeValue @310-314; FunctionDeclaration; parameters=1; async=false; generator=false
- UpdateHTMLAttributes @317-335; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveHTMLAttribute @337-353; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectHTMLTree @355-361; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdAEJSEAttributes.js

Blob: `30b8b4617ab96e8d882ee8cfe02fdf4b5401a61a`. Role: source. Parse: module.

- BuildJSEAttributeNameList @8-69; FunctionDeclaration; parameters=0; async=false; generator=false
- BuildJSEAttributeTable @72-98; FunctionDeclaration; parameters=0; async=false; generator=false
- onSelectJSEAttribute @100-109; FunctionDeclaration; parameters=0; async=false; generator=false
- onSelectJSETreeItem @111-126; FunctionDeclaration; parameters=0; async=false; generator=false
- onInputJSEAttributeValue @128-140; FunctionDeclaration; parameters=0; async=false; generator=false
- editJSEAttributeValue @142-146; FunctionDeclaration; parameters=1; async=false; generator=false
- UpdateJSEAttributes @148-168; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveJSEAttribute @170-199; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdAdvancedEdit.js

Blob: `2777b0caf6a4518d080099b75bf09b4061d5c697`. Role: source. Parse: module.

- Startup @40-107; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @115-130; FunctionDeclaration; parameters=0; async=false; generator=false
- doRemoveAttribute @135-144; FunctionDeclaration; parameters=1; async=false; generator=false
- doSetAttribute @146-155; FunctionDeclaration; parameters=2; async=false; generator=false
- CheckAttributeNameSimilarity @164-171; FunctionDeclaration; parameters=2; async=false; generator=false
- UpdateExistingAttribute @180-210; FunctionDeclaration; parameters=3; async=false; generator=false
- GetAndSelectExistingAttributeValue @217-251; FunctionDeclaration; parameters=2; async=false; generator=false
- GetTreeItemAttributeStr @259-267; FunctionDeclaration; parameters=1; async=false; generator=false
- GetTreeItemValueStr @269-277; FunctionDeclaration; parameters=1; async=false; generator=false
- SetTreeItemValueStr @279-283; FunctionDeclaration; parameters=2; async=false; generator=false
- IsNotTreeHeader @285-291; FunctionDeclaration; parameters=1; async=false; generator=false
- RemoveNameFromAttArray @293-301; FunctionDeclaration; parameters=2; async=false; generator=false
- AddTreeItem @304-331; FunctionDeclaration; parameters=4; async=false; generator=false
- selectTreeItem @333-336; FunctionDeclaration; parameters=2; async=false; generator=false
- getSelectedItem @338-343; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdColorPicker.js

Blob: `251d971bca3a2aa6c49c000229820d29a92a4c9d`. Role: source. Parse: module.

- Startup @25-169; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectColor @171-176; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveColor @178-182; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectColorByKeypress @184-189; FunctionDeclaration; parameters=1; async=false; generator=false
- SelectLastPickedColor @191-199; FunctionDeclaration; parameters=0; async=false; generator=false
- SetCurrentColor @201-212; FunctionDeclaration; parameters=1; async=false; generator=false
- SetColorSwatch @214-219; FunctionDeclaration; parameters=0; async=false; generator=false
- SetDefaultToOk @221-225; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateData @227-244; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @246-277; FunctionDeclaration; parameters=1; async=false; generator=false
- onCancelColor @279-283; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdColorProps.js

Blob: `23ddb707cf79c43d7994907de7e39a3bb39ff3c2`. Role: source. Parse: module.

- Startup @54-104; FunctionDeclaration; parameters=0; async=false; generator=false
- InitDialog @106-174; FunctionDeclaration; parameters=0; async=false; generator=false
- GetColorAndUpdate @176-253; FunctionDeclaration; parameters=1; async=false; generator=false
- SetColorPreview @255-280; FunctionDeclaration; parameters=2; async=false; generator=false
- UseCustomColors @282-305; FunctionDeclaration; parameters=0; async=false; generator=false
- UseDefaultColors @307-332; FunctionDeclaration; parameters=0; async=false; generator=false
- chooseFile @334-342; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @336-341; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ChangeBackgroundImage @344-347; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateAndPreviewImage @349-374; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateData @376-431; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @433-466; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @441-447; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @448-450; ArrowFunctionExpression; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdConvertToTable.js

Blob: `6d1900fe3623098922d143334ec549d8eafbc3bf`. Role: source. Parse: module.

- Startup @17-46; FunctionDeclaration; parameters=0; async=false; generator=false
- InputSepCharacter @48-62; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectCharacter @64-68; FunctionDeclaration; parameters=1; async=false; generator=false
- onAccept @70-319; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdDialogCommon.js

Blob: `c289da5f0d28d7d82d687cdac67400cd58e38810`. Role: source. Parse: module.

- ValidateNumber @56-110; FunctionDeclaration; parameters=7; async=false; generator=false
- ValidateNumberRange @128-167; FunctionDeclaration; parameters=4; async=false; generator=false
- ShowInputErrorMessage @169-172; FunctionDeclaration; parameters=1; async=false; generator=false
- GetAppropriatePercentString @179-195; FunctionDeclaration; parameters=2; async=false; generator=false
- ClearListbox @197-204; FunctionDeclaration; parameters=1; async=false; generator=false
- forceInteger @206-225; FunctionDeclaration; parameters=1; async=false; generator=false
- InitPixelOrPercentMenulist @227-279; FunctionDeclaration; parameters=5; async=false; generator=false
- onAdvancedEdit @281-301; FunctionDeclaration; parameters=0; async=false; generator=false
- getColor @303-318; FunctionDeclaration; parameters=1; async=false; generator=false
- setColorWell @320-336; FunctionDeclaration; parameters=2; async=false; generator=false
- SwitchToValidatePanel @338-341; FunctionDeclaration; parameters=0; async=false; generator=false
- GetLocalFileURL @346-393; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @383-392; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @384-391; ArrowFunctionExpression; parameters=1; async=false; generator=false
- SetWindowLocation @395-414; FunctionDeclaration; parameters=0; async=false; generator=false
- SaveWindowLocation @416-421; FunctionDeclaration; parameters=0; async=false; generator=false
- onCancel @423-425; FunctionDeclaration; parameters=0; async=false; generator=false
- FillLinkMenulist @457-568; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @534-542; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @556-566; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createMenuItem @570-578; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @573-576; ArrowFunctionExpression; parameters=0; async=false; generator=false
- chooseLinkFile @581-589; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @582-588; ArrowFunctionExpression; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdDictionary.js

Blob: `2bb9a775e31da66b939ab2d91c581aba272ff320`. Role: source. Parse: module.

- (anonymous) @10-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Startup @14-41; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateWordToAdd @43-49; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectWordToAddInList @51-59; FunctionDeclaration; parameters=0; async=false; generator=false
- AddWord @61-77; FunctionDeclaration; parameters=0; async=false; generator=false
- RemoveWord @79-97; FunctionDeclaration; parameters=0; async=false; generator=false
- FillDictionaryList @99-122; FunctionDeclaration; parameters=0; async=false; generator=false
- ResetSelectedItem @124-137; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdHLineProps.js

Blob: `9a3eb9e4ab3c19a04a0fef8729b633305c4080a9`. Role: source. Parse: module.

- Startup @19-59; FunctionDeclaration; parameters=0; async=false; generator=false
- InitDialog @64-112; FunctionDeclaration; parameters=0; async=false; generator=false
- onSaveDefault @114-155; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateData @159-214; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @216-225; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdImageDialog.js

Blob: `28b4f32de827079ac24a8f5b8d13f3337b9dc4e0`. Role: source. Parse: module.

- ImageStartup @44-70; FunctionDeclaration; parameters=0; async=false; generator=false
- InitImage @75-165; FunctionDeclaration; parameters=0; async=false; generator=false
- SetSizeWidgets @167-190; FunctionDeclaration; parameters=2; async=false; generator=false
- SetAltTextDisabled @193-195; FunctionDeclaration; parameters=1; async=false; generator=false
- GetImageMap @197-212; FunctionDeclaration; parameters=0; async=false; generator=false
- chooseFile @214-229; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @222-228; ArrowFunctionExpression; parameters=1; async=false; generator=false
- PreviewImageLoaded @231-266; FunctionDeclaration; parameters=0; async=false; generator=false
- LoadPreviewImage @268-297; FunctionDeclaration; parameters=0; async=false; generator=false
- SetActualSize @299-305; FunctionDeclaration; parameters=0; async=false; generator=false
- ChangeImageSrc @307-316; FunctionDeclaration; parameters=0; async=false; generator=false
- doDimensionEnabling @318-339; FunctionDeclaration; parameters=0; async=false; generator=false
- doOverallEnabling @341-348; FunctionDeclaration; parameters=0; async=false; generator=false
- ToggleConstrain @350-362; FunctionDeclaration; parameters=0; async=false; generator=false
- constrainProportions @364-417; FunctionDeclaration; parameters=2; async=false; generator=false
- removeImageMap @419-423; FunctionDeclaration; parameters=0; async=false; generator=false
- SwitchToValidatePanel @425-433; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateImage @437-628; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdImageLinkLoader.js

Blob: `4554fc94c6e1ed3c9cda737ee5518261d3ea0e50`. Role: source. Parse: module.

- OnLoadDialog @16-43; FunctionDeclaration; parameters=0; async=false; generator=false
- OnAcceptDialog @45-57; FunctionDeclaration; parameters=0; async=false; generator=false
- SetAttachCheckbox @59-103; FunctionDeclaration; parameters=0; async=false; generator=false
- DoAttachSourceCheckbox @105-112; FunctionDeclaration; parameters=0; async=false; generator=false
- GenerateDataURL @114-141; FunctionDeclaration; parameters=1; async=false; generator=false

### mail/components/compose/content/dialogs/EdImageProps.js

Blob: `16d160ec8b62619345c022e02dd6eb88292f2062`. Role: source. Parse: module.

- Startup @18-114; FunctionDeclaration; parameters=0; async=false; generator=false
- InitDialog @119-123; FunctionDeclaration; parameters=0; async=false; generator=false
- ChangeLinkLocation @125-131; FunctionDeclaration; parameters=0; async=false; generator=false
- ToggleShowLinkBorder @133-142; FunctionDeclaration; parameters=0; async=false; generator=false
- ValidateData @146-148; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @150-270; FunctionDeclaration; parameters=1; async=false; generator=false
- onLinkAdvancedEdit @272-285; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdInsSrc.js

Blob: `7a66627c71963e071d6f369dc20a2a0a42bc2643`. Role: source. Parse: module.

- Startup @18-58; FunctionDeclaration; parameters=0; async=false; generator=false
- replaceDataURIs @60-92; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @63-90; FunctionExpression; parameters=3; async=false; generator=false
- onCopyOrCut @94-121; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @105-111; FunctionExpression; parameters=3; async=false; generator=false
- onPaste @123-138; FunctionDeclaration; parameters=1; async=false; generator=false
- onAccept @140-163; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @150-156; FunctionExpression; parameters=3; async=false; generator=false

### mail/components/compose/content/dialogs/EdInsertChars.js

Blob: `640587d56a6749ec7fd647e588d357dbb1f5f031`. Role: source. Parse: module.

- Startup @25-39; FunctionDeclaration; parameters=0; async=false; generator=false
- onAccept @41-55; FunctionDeclaration; parameters=1; async=false; generator=false
- onFocus @58-65; FunctionDeclaration; parameters=0; async=false; generator=false
- onClose @67-70; FunctionDeclaration; parameters=0; async=false; generator=false
- StartupLatin @89-141; FunctionDeclaration; parameters=0; async=false; generator=false
- ChangeCategory @143-151; FunctionDeclaration; parameters=1; async=false; generator=false
- SelectLatinLetter @153-159; FunctionDeclaration; parameters=0; async=false; generator=false
- SelectLatinModifier @161-166; FunctionDeclaration; parameters=0; async=false; generator=false
- DisableLatinL @167-170; FunctionDeclaration; parameters=1; async=false; generator=false
- UpdateLatinL @172-191; FunctionDeclaration; parameters=0; async=false; generator=false
- UpdateLatinM @193-265; FunctionDeclaration; parameters=0; async=false; generator=false
- UpdateCharacter @267-288; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdInsertMath.js

Blob: `087097e11b784f1c273149f3476933fc8f9e5fc4`. Role: source. Parse: module.

- Startup @13-110; FunctionDeclaration; parameters=0; async=false; generator=false
- insertLaTeXCommand @112-155; FunctionDeclaration; parameters=1; async=false; generator=false
- createCommandPanel @157-202; FunctionDeclaration; parameters=1; async=false; generator=false
- createSymbolPanels @204-248; FunctionDeclaration; parameters=1; async=false; generator=false
- onAccept @250-276; FunctionDeclaration; parameters=1; async=false; generator=false
- updateMath @278-300; FunctionDeclaration; parameters=0; async=false; generator=false
- updateMode @302-309; FunctionDeclaration; parameters=0; async=false; generator=false
- updateDirection @311-318; FunctionDeclaration; parameters=0; async=false; generator=false

### mail/components/compose/content/dialogs/EdInsertTOC.js

Blob: `5ad5ab42699966430144cb5cb269362ee4e2ddb3`. Role: source. Parse: module.

- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Startup @34-132; FunctionDeclaration; parameters=0; async=false; generator=false
- BuildTOC @134-357; FunctionDeclaration; parameters=1; async=false; generator=false
- controlClass @138-156; FunctionDeclaration; parameters=2; async=false; generator=false
- acceptNode @161-178; FunctionDeclaration; parameters=1; async=false; generator=false
- selectHeader @359-368; FunctionDeclaration; parameters=2; async=false; generator=false
- changeClass @370-372; FunctionDeclaration; parameters=2; async=false; generator=false
- ToggleReadOnlyToc @374-376; FunctionDeclaration; parameters=1; async=false; generator=false
- ToggleOrderedList @378-380; FunctionDeclaration; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
