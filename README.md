# FamilyWire language packs

This repository preserves FamilyWire's verified offline translation packs and their
licenses/provenance. The initial EN↔ES pack is being prepared; no downloadable pack
release exists yet. FamilyWire 1.4 and its automatic-update feed are unchanged.

Planned immutable release: `en-es-v1.0.1`, assets `en-es.fwlp` and signed `manifest.json`.
The 16 converted model files retain the pinned ONNX Community/Helsinki-NLP source
revisions, original cards, Apache-2.0 and CC-BY-4.0 legal texts and attribution notices.
Only small recipes, manifests, licenses/provenance and checksums belong in Git.
Model binaries belong in release assets; Git LFS is not used.

Manifest trust uses Ed25519, key ID `familywire-en-es-release-v1`.
Public SPKI DER SHA-256:
`4fe402ab27a766ec159e4a13f28779d63bc9daf57fd162af7dc28a8851099934`.
Private signing material is never stored here or in CI.

A manual FamilyWire 1.5.0 app prerelease remains gated on signed-byte verification,
recovery backup readback and disposable installed/native offline acceptance.
