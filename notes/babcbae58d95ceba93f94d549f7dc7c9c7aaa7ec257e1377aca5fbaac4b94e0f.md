<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T00:02:27.528Z","paths":["mail/themes/shared/mail/variables.css"],"source":{"reference":"knowledge-record:babcbae58d95ceba93f94d549f7dc7c9c7aaa7ec257e1377aca5fbaac4b94e0f","recordId":"babcbae58d95ceba93f94d549f7dc7c9c7aaa7ec257e1377aca5fbaac4b94e0f","status":"provisional","publicationKey":"a791d741761e193d96aca7dd3a101ddfd2071abd83ca0f408f9251ad98d2c8da"}} -->
# Secondary pressed-border token mismatch

The AI review record for D336388 at revision 938178e96fcd54acd48300758465d6feb76b68c9 reports that --secondary-button-border-active refers to undefined --color-surface-intense, causing the pressed border to use currentColor. It proposes --color-surface-border-intense, citing the parent Account Hub style, and reports restored border colors in light and dark Thunderbird experiments. Use this as a scoped lead when checking the shared secondary button mapping. No raw experiment output, human confirmation, or landed correction is supplied.

Scope: Shared secondary button colors.

## Evidence

[Lesson record](../records/babcbae58d95ceba93f94d549f7dc7c9c7aaa7ec257e1377aca5fbaac4b94e0f.json).

- [Supporting record](../records/fa02e1fba5ad8b17b449528d5fcea10a841fa51d3fd7050ff0273087c0770c43.json)

## Validation and limits

Status: **provisional**. Recorded interpretation. Original private evidence is unavailable to other consumers; this summary is not independent verification.
