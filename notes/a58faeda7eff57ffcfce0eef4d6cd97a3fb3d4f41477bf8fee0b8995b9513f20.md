<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T23:00:02.814Z","paths":["mail/metrics.yaml","calendar/base/modules/utils/calProviderUtils.sys.mjs","mail/components/accountcreation/modules/ConfigVerifier.sys.mjs","mailnews/addrbook/modules/CardDAVUtils.sys.mjs"],"source":{"reference":"knowledge-record:a58faeda7eff57ffcfce0eef4d6cd97a3fb3d4f41477bf8fee0b8995b9513f20","recordId":"a58faeda7eff57ffcfce0eef4d6cd97a3fb3d4f41477bf8fee0b8995b9513f20","status":"supported","publicationKey":"d0f206c417c9b9a4c0f9283570d399f1e6b02caf305e0f74223b97f408527cc0"}} -->
# Certificate exception events mark specific UI acceptance actions before retry completion

The certificate exception event records the error category, protocol, port and UI at instrumented exception-acceptance paths. Configuration verification and CardDAV record before retrying, so the event does not establish a successful retry or login. Calendar records after acceptance even when there is no refreshable calendar. Coverage is limited to the instrumented call sites; the commit explicitly omits several other exception UIs. The schema uses string extras, while source fixtures contain both numeric and string ports; no generated conversion was checked. No event or test was executed.

Scope: Scoped certificate exception telemetry boundary.

## Evidence

[Lesson record](../records/a58faeda7eff57ffcfce0eef4d6cd97a3fb3d4f41477bf8fee0b8995b9513f20.json).

- [Supporting record](../records/5296843e1f8389e07824331b2d3bd781b4f782f729ba9d62f5db146759f89adf.json)
- [Supporting record](../records/772863e2427bf7acd46cb05ee87861231841b448cea37efd2f149c0d7d289bfb.json)
- [Supporting record](../records/afc1a46bf8c9a11a85f405f37cd4ef0f16f4e1d432c75e02ae6878711c4bf8c0.json)
- [Supporting record](../records/bec0bdabf9670be71f5c5840a11b78a4bf923b0a46eeca3e2d211cb80f068838.json)
- [Supporting record](../records/fd0c475fcab0f5036796f6b05af3730f6a479be86fd6c848fe3a83e2f6945ee2.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
