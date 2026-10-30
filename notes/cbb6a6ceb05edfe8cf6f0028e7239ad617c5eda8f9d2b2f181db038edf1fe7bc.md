<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T10:53:23.849Z","paths":["mail/components/compose/content/dialogs/EdSpellCheck.js","mail/components/extensions/parent/ext-mail.js"],"source":{"reference":"knowledge-record:cbb6a6ceb05edfe8cf6f0028e7239ad617c5eda8f9d2b2f181db038edf1fe7bc","recordId":"cbb6a6ceb05edfe8cf6f0028e7239ad617c5eda8f9d2b2f181db038edf1fe7bc","status":"supported","publicationKey":"5013ce5be276d5dc6f0b90cba594d6ef25d00ab5eb911c9f26ebb6819111aac8"}} -->
# Spell-dialog opener access stays direct while tab lookup retains a Window fallback

The original port captures the spell dialog's previous focus with window.opener.document.activeElement, rather than adding documentGlobal to the opener Window. Its tab-browser helper also keeps a mixed wrapper-or-Window fallback: ownerGlobal ?? nativeTabInfo, then getBrowser when available. Fixed accepted source retains both forms. These concrete exceptions show why a port must check the actual receiver; they do not define a global ban on ownerGlobal or prove paired native property semantics. Focus capture/restoration is static source scope only.

Scope: Document and Window receivers in the property port.

## Evidence

[Lesson record](../records/cbb6a6ceb05edfe8cf6f0028e7239ad617c5eda8f9d2b2f181db038edf1fe7bc.json).

- [Supporting record](../records/3f7662744058b11ad0286f0db452dddc76055c6406aafd7ef56cbbcde53fa4ad.json)
- [Supporting record](../records/85e5bc3453dc7c26761162ccf6e2e994b095f6e9268a60d7abba1db84b68fd42.json)
- [Supporting record](../records/9ebae694644be75d9abb564151efa3e34389faeb47286ca8979c6da1953fd97c.json)
- [Supporting record](../records/ffaa97c15987011d02ebc091fb683e9752a40f689cbd336614c43eb8431ecdb8.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
