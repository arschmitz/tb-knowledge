<!-- knowledge: {"repository":"thunderbird","at":"2026-10-14T01:31:37.609Z","paths":["mailnews/compose/src/nsMsgSendLater.cpp","mailnews/compose/test/unit/test_sendMessageLater_dsn_message_id.js"],"source":{"reference":"knowledge-record:cee117a8c7ac284feb9d4a2ac45eb7cbf8b6f1495ca9deb7053ac67f7daf4e2b","recordId":"cee117a8c7ac284feb9d4a2ac45eb7cbf8b6f1495ca9deb7053ac67f7daf4e2b","status":"supported","publicationKey":"9049bbaba14710da34f56293ae9ed69b064bf37eaafa6939d373ec815cd077e2"}} -->
# Delayed-send identity tests assert the SMTP envelope identifier

The delayed-send path extracts the queued Message-ID or generates one, then calls fields->SetMessageId before SendMessageFile. The 763 tests queue fixtures with and without a Message-ID and match RET=FULL ENVID in the fake SMTP MAIL FROM command. They also check one attempted send, one success and stopped sending state. They do not assert the delivered serialized header. This corrects the older note that described joint verification of envelope and delivered-header identity. The frozen test anchors its ENVID expression to the end of the command and later repeats a header-bearing fixture to catch doubled IDs. Source ordering supports the composition-field contract; it does not by itself establish serialization agreement in a live SMTP transaction. No test or protocol transaction ran in this study.

Scope: Delayed-send message identity.

## Evidence

[Lesson record](../records/cee117a8c7ac284feb9d4a2ac45eb7cbf8b6f1495ca9deb7053ac67f7daf4e2b.json).

- [Supporting record](../records/20e006c9e8f8c68a2b946e5cd26e6908ee280fc9684d2b7f0af379f776d31d38.json)
- [Supporting record](../records/4a7de2eee68d8d2d43d28a6b333c38f38f971c62699c0677b371bbe49e480122.json)
- [Supporting record](../records/4c69ce3e1b26d0cbfc089991bdd45d3f9d2de0c190aee793f572f164363d6313.json)
- [Supporting record](../records/6ee1b339445aad6186fd83dcd4f71c194193602388909e3c85778ac1db7ff811.json)
- [Supporting record](../records/bbae8b9afd79e48f666fc5dd9a92418ec7e93c1fff69fdbcf221457722bbc0b5.json)
- [Supporting record](../records/d066cdef0bc9aafe47a66b0a87aeeeee760204ea620af1178d10b786c793d9cc.json)
- [Supporting record](../records/e8b830a14e48ba2e7be865967ceb5613a1f31f7345d841ecdc0776aadd160fb7.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
