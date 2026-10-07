<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:11:16.030Z","paths":["docs/mach_commands.py"],"source":{"reference":"knowledge-record:6c3a7d4654b6fcfb9fdb1e22a9ffdb1d2bc855ff2f3440c5db9b19eda72ed00b","recordId":"6c3a7d4654b6fcfb9fdb1e22a9ffdb1d2bc855ff2f3440c5db9b19eda72ed00b","status":"supported","publicationKey":"e9ddd00293d6f52deba8fefdd6f62649813d321654b8464d3ad5862ccb4e255b"}} -->
# Check the documentation error classifier against complete diagnostic lines

The accepted _check_sphinx_errors only enters its error branch when a whole warning string equals ERROR or CRITICAL. A string containing either word plus a message or a newline does not meet that exact equality. The neighboring warning-count helper searches within each line. This is an unresolved static diagnostic-classification concern, not a reproduced build failure; the actual emitted Sphinx diagnostics and review intent remain to be verified.

Scope: Source documentation error-line classification.

## Evidence

[Lesson record](../records/6c3a7d4654b6fcfb9fdb1e22a9ffdb1d2bc855ff2f3440c5db9b19eda72ed00b.json).

- [Supporting record](../records/0b2da61c845ef048146bbc765c79a703f435ce345ed2ce8878b1826fb46a8576.json)
- [Supporting record](../records/18b93e3c22e9be1f9d9e272b02ab0fc68cc4112a9f2172b309707ec5c896bea3.json)
- [Supporting record](../records/3874a8a42f152f0cc956b24c02699d5893e3a70b20818b97052469f9152cb33e.json)
- [Supporting record](../records/68a7b92aa43d609f4bd84294408754a348c6cd5cd18499be39849632e737d46b.json)
- [Supporting record](../records/7fd7d0b984afcb1bf4d790dd7f512cd67c3dcacde74d915f6eb593762d843304.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
