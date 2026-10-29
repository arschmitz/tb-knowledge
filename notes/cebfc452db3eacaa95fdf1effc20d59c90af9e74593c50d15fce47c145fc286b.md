<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T14:18:17.504Z","paths":["rust/ms_graph_tb/src/types/user.rs","rust/ms_graph_tb/ms_graph_tb_extract/src/extract/schema.rs","rust/ms_graph_tb/ms_graph_tb_extract/src/oxidize/types.rs"],"source":{"reference":"knowledge-record:cebfc452db3eacaa95fdf1effc20d59c90af9e74593c50d15fce47c145fc286b","recordId":"cebfc452db3eacaa95fdf1effc20d59c90af9e74593c50d15fce47c145fc286b","status":"supported","publicationKey":"e2ad82ce6ab05d5da56c8a1d33f2740a3540d02066165e64f8e08daf60809496"}} -->
# Generated Graph descriptions and nullable accessors need separate checks

The generated usage_location description says Not nullable, but its Result<Option<&str>, Error> getter returns Ok(None) for JSON null. The extractor obtains the nullable flag from schema metadata separately from the copied description, and the emitter uses that flag for Option and the null branch. This source mismatch does not establish whether the description or the flag is wrong. Check both when changing the generator; the upstream schema and a runtime case were not inspected here.

Scope: Initial Graph nullable output documentation.

## Evidence

[Lesson record](../records/cebfc452db3eacaa95fdf1effc20d59c90af9e74593c50d15fce47c145fc286b.json).

- [Supporting record](../records/4037844e0908ff8b06bbaf1b0415bee38327b64ccf1b19a9fa575d7fab4c6159.json)
- [Supporting record](../records/4d151d188f8dd13c473c4402d54a12ea0efb9258ac83630a3a701a2e51e468d3.json)
- [Supporting record](../records/50e39e944c26a7a72e85443c772858187437438c6ebe30de0df8ae2abe0e52b7.json)
- [Supporting record](../records/dc1f2dd75db8f0559e9bb8bc57a4eee8904c4688c8d4a78d63dc150ca287a0ab.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
