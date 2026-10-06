<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.145Z","paths":["mailnews/imap/test/unit/test_imapAttachmentSaves.js"],"source":{"reference":"https://phabricator.services.mozilla.com/D264829","status":"supported","publicationKey":"9b0fa9787dcb572e3d1a98b2f5ec4569ddd3ea01f64157d24d3d33f39c9c3ce2"}} -->
# Use class syntax for new JavaScript listener objects

For a new listener object with methods and state, use JavaScript class syntax instead of a constructor function plus prototype assignments. This makes the object shape visible in one place.

Scope: style-syntax.

Paths:

- `mailnews/imap/test/unit/test_imapAttachmentSaves.js`

## Evidence

[Shared lesson record](../records/6525a170259eeaddcf0a85d449ec2c5a6d2ed64008970ac82497d485d17db385.json).

- https://phabricator.services.mozilla.com/D264829
- https://github.com/thunderbird/thunderbird-desktop/commit/b92c02271319

Source record: `c75d3a540fa152d1291eabf05a698166edfedd2ac0f19ec342fc01a3b86461fb`

~~~
class syntactic sugar rather than doing the function/prototype thing
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `6cd37ffe8fef12b0203ce8566e48a3e41519a8f794e5bef9d16bfea7dc11cf35`.
