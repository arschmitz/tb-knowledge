<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:45:06.313Z","paths":["mailnews/base/src/MboxMsgInputStream.cpp"],"source":{"reference":"knowledge-record:3d1a2f2acdf543ea0e85fa6ddb93f4a29859d9be07ee62b0fad0c3df255bb4ce","recordId":"3d1a2f2acdf543ea0e85fa6ddb93f4a29859d9be07ee62b0fad0c3df255bb4ce","status":"supported","publicationKey":"def855856324278cf040c9d1c60030c37bdc764169523eef89e8c9820587472a"}} -->
# Mbox constructor safety differs from caller locking after publication

A later accepted change removed constructor locking because other threads cannot access the object during construction. PumpData remains an internal helper that does not lock; its caller must provide a thread-safe state. Thus the constructor can pump before publication, while public Read/Continue paths lock. This is the checked object-lifecycle contract, not a rule to omit locks from all constructors. This is static source and test-code inspection. Complete Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mailnews/base/src.

## Evidence

[Lesson record](../records/3d1a2f2acdf543ea0e85fa6ddb93f4a29859d9be07ee62b0fad0c3df255bb4ce.json).

- [Supporting record](../records/1d746a6abc1839489309af02aa829d100422358ea9ea92d649257b1c453543e0.json)
- [Supporting record](../records/469e4e7ce93181df7aa48a57ad6671dd67760bdeb793ccb21d5afb11c06d3ddb.json)
- [Supporting record](../records/502e6a6f3724974c619e75207ad8deabc18ba613c0488686c45cebd8df8bbdb0.json)
- [Supporting record](../records/5ea1ba01961dd10b56b8cde8ca026512027f8c2c4b1ca7854ebdba297a387ec4.json)
- [Supporting record](../records/7a6daaea64b4d79c5a821f8a33757a36960b9aeffbf9af0c1c25a0700087365d.json)
- [Supporting record](../records/7acef17d2d0f240492cdec02dd5e15a922e8f5f708cb6a0e7a13cc1fdfc54eee.json)
- [Supporting record](../records/beb7957f98b3ba9fa296c43e22b9754cab9f517d997517b5c73eb633c7101e16.json)
- [Supporting record](../records/d9bada359a6c87c83e4500c7a1cf02881fea5775e3766f0bb2aa6802d28ed983.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
