<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:11:16.007Z","paths":["mailnews/local/src/nsLocalMailFolder.cpp"],"source":{"reference":"knowledge-record:37e76b2cdd378ad6f7aabdbfedcfbcb12cce4aabc10c43d81718998ac6dcb97f","recordId":"37e76b2cdd378ad6f7aabdbfedcfbcb12cce4aabc10c43d81718998ac6dcb97f","status":"supported","publicationKey":"131e94d55e6f1b4547d58cdd08a57c94643229ed5bc38aff79e6cc6cd87a6f90"}} -->
# Give local mail copy state defined defaults before later setup

940 initializes folder, multiple-message, from-line and undo booleans to false in the constructor. The accepted constructor retains the folder/multiple/undo defaults; m_fromLineSeen is no longer a field in the inspected class. InitCopyState later supplies operation values, and the multiple-copy flag controls stream setup and message indexing. Preserve constructor validity before that later setup instead of relying on a single caller to initialize every path.

Scope: Local mail copy state initialization.

## Evidence

[Lesson record](../records/37e76b2cdd378ad6f7aabdbfedcfbcb12cce4aabc10c43d81718998ac6dcb97f.json).

- [Supporting record](../records/0fe59ec1c7de9a65ccbad97b413a6f285c9d8b967e41ffd40ac338ee1812b3ee.json)
- [Supporting record](../records/18580b0daa9b42c1799580a6e5f62371545cf474eb92f833ad7639e6c010ff7f.json)
- [Supporting record](../records/5409c4049704a1f713ef80dac5f3c42d7e789c6de8503173dc49a7b344e1fcc5.json)
- [Supporting record](../records/8411f54f74d2c098cf5a945657d9df5ae45e5669bc76f0cf5de274c512067738.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
