<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T00:33:54.794Z","paths":["taskcluster/docker/tb-flatpak/repack.sh"],"source":{"reference":"knowledge-record:f9e4a6c4ee67aecca759f8ccb6e80c5278f5e56f17f3ad1f43ea664f8fdbc2bc","recordId":"f9e4a6c4ee67aecca759f8ccb6e80c5278f5e56f17f3ad1f43ea664f8fdbc2bc","status":"supported","publicationKey":"c259553ae65cb20e5b9c1b62788e0eb6fbfba00d8655d80d8aa5e6eea121c32b"}} -->
# Flatpak repack connects the runtime version and BaseApp channel to separate package refs

The historical24.08 update changes both FREEDESKTOP_VERSION and FIREFOX_BASEAPP_CHANNEL. In the checked accepted script, the first supplies the platform/sdk refs; the second selects the installed Firefox BaseApp and metadata base ref. Current values are25.08, a later source phase. When changing this repack recipe, check both named values and their consumers. This is scoped packaging evidence, not a universal requirement that arbitrary runtimes share versions. No external package existence, build or runtime behavior was verified.

Scope: Flatpak packaging.

## Evidence

[Lesson record](../records/f9e4a6c4ee67aecca759f8ccb6e80c5278f5e56f17f3ad1f43ea664f8fdbc2bc.json).

- [Supporting record](../records/40ef0aec11ad7ba872f290d16b21de878dbd54e967520a6f77fd1f6f892aa918.json)
- [Supporting record](../records/48dc6a785ff47510559f3a788602c82cb98fb1ca0a948b86b60b5f5715f6c056.json)
- [Supporting record](../records/bd42ab475a2de6ce256e16249bcc0cee26c542eefe6e59db086dbf178aec9506.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
