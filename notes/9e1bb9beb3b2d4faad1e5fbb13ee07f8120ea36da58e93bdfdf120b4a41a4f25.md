<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T08:26:23.130Z","paths":["mail/themes/shared/mail/variables.css","mail/themes/shared/mail/threadCard.css","mail/themes/shared/mail/widgets.css"],"source":{"reference":"knowledge-record:9e1bb9beb3b2d4faad1e5fbb13ee07f8120ea36da58e93bdfdf120b4a41a4f25","recordId":"9e1bb9beb3b2d4faad1e5fbb13ee07f8120ea36da58e93bdfdf120b4a41a4f25","status":"supported","publicationKey":"a6c8344bf39d394eecc112cc91cbf1d92aeb67ff3c3212e69395d009dc092f2e"}} -->
# Removing the contrast theme guard leaves other theme and state conditions intact

This later CSS phase removes root not-lwtheme guards from positive prefers-contrast branches. It preserves separate conditions, including the noncontrast not-lwtheme branch and the minimonth light-theme ancestor rule. The owned button edit also changes nesting/order: its contrast-hover border sits before the nested active override. Read media, theme and local state together; this patch is not permission to remove every theme guard or proof that all cascades are equivalent. Selected accepted source keeps contrast scope, but no computed style or platform/theme check ran.

Scope: Thunderbird contrast CSS condition scope.

## Evidence

[Lesson record](../records/9e1bb9beb3b2d4faad1e5fbb13ee07f8120ea36da58e93bdfdf120b4a41a4f25.json).

- [Supporting record](../records/19e83c3338ba5d78fabdca58339f8282bad336010398b3be669a7653e3cb8d01.json)
- [Supporting record](../records/677d26be4816ed89257fdddea14f4396eca33a0b1cbdf3fdb043ca4433eb2e13.json)
- [Supporting record](../records/8334da3cc29ca153ee361ef239575afb23b699b574b62cfef1388581e343c85e.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
