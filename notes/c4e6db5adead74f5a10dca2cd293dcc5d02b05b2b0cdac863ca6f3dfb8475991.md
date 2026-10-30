<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T04:20:12.532Z","paths":["mailnews/base/src/nsMsgI18N.cpp","mailnews/base/src/nsMsgI18N.h","mailnews/base/src/nsMsgDBFolder.cpp","mailnews/base/test/gtest/TestMsgI18N.cpp","mailnews/base/public/nsIMsgFolder.idl"],"source":{"reference":"knowledge-record:c4e6db5adead74f5a10dca2cd293dcc5d02b05b2b0cdac863ca6f3dfb8475991","recordId":"c4e6db5adead74f5a10dca2cd293dcc5d02b05b2b0cdac863ca6f3dfb8475991","status":"supported","publicationKey":"82fe35a1213716d6c2d4863fb06f796124ffb7754d84760251f6ebde3152312d"}} -->
# The UTF-8 helper size change stops at the message-text interface

The follow-up changes maxBytes to size_t in the helper and its table test, then casts the production aMaxOutputLen argument at the call. The native entrypoint still receives uint32_t and the IDL still declares unsigned long. The author and reviewer explicitly agree to stop propagation there, and exact source adopts that boundary. This adds no new test cases or interface widening and does not establish a global size_t or ABI rule. Accepted source retains the boundary while later changing the truncation algorithm.

Scope: MailNews UTF-8 helper and XPCOM caller boundary.

## Evidence

[Lesson record](../records/c4e6db5adead74f5a10dca2cd293dcc5d02b05b2b0cdac863ca6f3dfb8475991.json).

- [Supporting record](../records/209117c93b871bcaeb11efb2b5459a64be7ad086262c8ec1e52c3c07815807f7.json)
- [Supporting record](../records/2649f89605b5475e2bbc139d2f97058eb7bec20d8b22cccb7fd525bed13ad845.json)
- [Supporting record](../records/4f7bec219a588b29e2f3aebf260506b32d73df75da29cbcd44c5544a02213fdd.json)
- [Supporting record](../records/867f7bc18891f6f7608b6be03dd22b59f225a340550c76db60721ed7d5cfcf86.json)
- [Supporting record](../records/9a95f715df9ec4cef2fe220bc6b473a393166009bf94c21eb0c3fed0452811cf.json)
- [Supporting record](../records/9e73dcefffaf716454eebf4a5e5084b374917837f38481a89f3ec7a20f8c3628.json)
- [Supporting record](../records/d0f08b987bb57ee67dfe837685c773791c1d7170c246ff2eb154aed886cb56f4.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
