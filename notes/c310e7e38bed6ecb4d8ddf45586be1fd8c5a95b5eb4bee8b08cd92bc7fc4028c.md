<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T05:53:26.660Z","paths":["mail/components/extensions/MessagesSendTracker.sys.mjs","mail/components/extensions/test/xpcshell/test_ext_messages_send.js","mail/locales/en-US/messenger/activity.ftl"],"source":{"reference":"knowledge-record:c310e7e38bed6ecb4d8ddf45586be1fd8c5a95b5eb4bee8b08cd92bc7fc4028c","recordId":"c310e7e38bed6ecb4d8ddf45586be1fd8c5a95b5eb4bee8b08cd92bc7fc4028c","status":"supported","publicationKey":"2a3d44a49c0e9c87ac509fb5080207a4a9d49f1c1fb5c344fc410dac7911f2fe"}} -->
# Completed extension send status receives a localized duration string

SendTracker.flush rounds the completed batch span to at least one second, formats it with Intl.DurationFormat and supplies count/time to extension-sent-activity-event-status. Fluent pluralizes the count and embeds the duration string. The single-message test asserts count and duration substrings separately, so it does not prove exact combined wording, all locales or idle-timer expiry.

Scope: WebExtension completed send activity localization.

## Evidence

[Lesson record](../records/c310e7e38bed6ecb4d8ddf45586be1fd8c5a95b5eb4bee8b08cd92bc7fc4028c.json).

- [Supporting record](../records/32cf0add118f4cc7bc0cca2656f99181e7ba608fcda91917a6c134f9115f834e.json)
- [Supporting record](../records/9fee13d0987908b8d55d5cfbe5e92586bf0ebd018ef32cba0a53a443c78d7b58.json)
- [Supporting record](../records/e5ad04a859bf02fd965024ce8eae9c01ac124e982ff1c716183e4de6fc82c8ea.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
