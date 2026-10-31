<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T12:20:01.165Z","paths":["mail/extensions/openpgp/test/unit/rnp/test_externalSigningKey.js"],"source":{"reference":"knowledge-record:bdf9e50be5bba4f5cac66b6242f3484bce8ef2ec6cfa8bfd8fbfc8a37c04ec26","recordId":"bdf9e50be5bba4f5cac66b6242f3484bce8ef2ec6cfa8bfd8fbfc8a37c04ec26","status":"supported","publicationKey":"baf3d757c978e7fdc604080b83531fc763390be174f4a8425fa8e74373afb811"}} -->
# The public signing-key selection test checks an ID without invoking GPGME

The new task imports an Ofelia public-key fixture, finds its primary handle and checks that findSuitableSigningKeyID returns the expected signing-subkey ID. Both assertions have expected-behavior messages. The task does not call GPGME or create/verify a signature; primary fallback, no candidate and invalid-subkey cases are outside its direct assertions. Native integration belongs to a separate follow-up test, and no test ran here.

Scope: OpenPGP key-selection unit-test coverage.

## Evidence

[Lesson record](../records/bdf9e50be5bba4f5cac66b6242f3484bce8ef2ec6cfa8bfd8fbfc8a37c04ec26.json).

- [Supporting record](../records/f8be93942c105ba6a638ca4f48327569836569cba79004d20737a9f255d21f8e.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
