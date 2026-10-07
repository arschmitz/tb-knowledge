<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T04:24:53.236Z","paths":["third_party/sax-js/moz.yaml","third_party/README.sax-js"],"source":{"reference":"knowledge-record:b8922ebb7ff57360e0bfbd7face42ec2dd86db3d06322dbcb98f6714faf1dfb6","recordId":"b8922ebb7ff57360e0bfbd7face42ec2dd86db3d06322dbcb98f6714faf1dfb6","status":"supported","publicationKey":"0470d322c69cdc40c6aa3bd6d716df6e5e5fea216fc03397af33fd4e6ca9c69f"}} -->
# Keep SAX update instructions and retained integration files together

The vendoring metadata preserves sax.sys.mjs, excludes upstream tests and examples from the import, and moves the upstream library directory into the installed layout. README.sax-js explains why update-moz-build is skipped and how to invoke vendoring. In this dependency family, keep the wrapper, update hooks and manual packaging explanation aligned when changing vendor layout. The documented commands were not run, and imported source formatting does not become a Thunderbird style rule. These conclusions come from static source inspection. No runtime test or accessibility session was run. Full Bugzilla and Phabricator discussion remains pending.

Scope: SAX vendor update ownership.

## Evidence

[Lesson record](../records/b8922ebb7ff57360e0bfbd7face42ec2dd86db3d06322dbcb98f6714faf1dfb6.json).

- [Supporting record](../records/552536cba5e94fb1790bb086938753dae368556fbcbf3051e5f87affdd137157.json)
- [Supporting record](../records/fb193010a9ea5bdcf044327cbe41ebc779b8bb63c725dc474e04229ca73d28f7.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
