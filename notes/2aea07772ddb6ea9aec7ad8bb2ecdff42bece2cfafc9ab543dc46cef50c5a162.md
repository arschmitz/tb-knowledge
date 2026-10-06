<!-- knowledge: {"repository":"tb-tools","at":"2026-10-06T22:10:06.677Z","paths":["commands/knowledge/publication.mjs"],"source":{"reference":"knowledge-record:2aea07772ddb6ea9aec7ad8bb2ecdff42bece2cfafc9ab543dc46cef50c5a162","recordId":"2aea07772ddb6ea9aec7ad8bb2ecdff42bece2cfafc9ab543dc46cef50c5a162","status":"provisional","publicationKey":"31c9cb377aa543cf00162593be45c4719146e104c8160cc21066553a21627173"}} -->
# Publication requires repository-matched evidence

In the supplied TB Tools revision, publishProjectLessons selects private lessons only from repositories listed in shareRepositories, then rejects publication if any referenced evidence is missing or belongs to another repository. This makes repository selection and evidence ownership explicit checks in this function. shareRepositories defaults to an empty array. These checks do not verify the truth of the evidence or establish the behavior of other publication routes.

Scope: TB Tools knowledge publication.

## Evidence

[Lesson record](../records/2aea07772ddb6ea9aec7ad8bb2ecdff42bece2cfafc9ab543dc46cef50c5a162.json).

- [Supporting record](../records/8df0c826f47729e5f3e319b7d90161c81ecafd359e7cc53cbc38a32da18cc89f.json)

## Validation and limits

Status: **provisional**. Recorded interpretation. Original private evidence is unavailable to other consumers; this summary is not independent verification.
