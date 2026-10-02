# FamilyWire language packs

Official optional desktop translation packs owned by Jeremy (`jgarne1`).

[EN↔ES offline pack 1.0.1](https://github.com/jgarne1/familywire-language-packs/releases/tag/en-es-v1.0.1) is published for FamilyWire 1.5.0 and compatible newer desktop releases. Supported targets are Windows x64, Intel Mac x64 and Apple Silicon Mac arm64. This repository does not change the app's existing 1.4.0 automatic release channel.

Use **Download now** in a compatible FamilyWire app. For offline recovery, keep `manifest.json` and `en-es.fwlp` in one folder, then select `manifest.json` with **Import offline pack**. The app verifies the Ed25519 signature, compatibility and every file hash before activation. Installed packs work offline and are kept independently of the app installation.

The release contains all 16 unchanged quantized ONNX Community model/tokenizer files from the pinned FamilyWire 1.4.0 EN↔ES bundle, expanded attribution, both complete license texts and public verification data. See `NOTICES.txt`, `APACHE-2.0.txt`, `CC-BY-4.0.txt` and `provenance.json` for upstream credits and exact converted-model revisions. The provenance does not claim a known source Helsinki commit or an exclusive split between the upstream license declarations.

Archive: 504,902,058 bytes; SHA-256 `24d22557a5223ee1d7d67e57f4ace498d5fb7a5d23119e7cba38e561bf7a1b02`.
Signed manifest SHA-256: `f1f814eb5c39ed55d65efafded49ed33c2ac91604b7a6b6a4eb46cffefa9f84d`.
Key ID: `familywire-en-es-release-v1`; public SPKI SHA-256 `4fe402ab27a766ec159e4a13f28779d63bc9daf57fd162af7dc28a8851099934`.

Release URLs are version-pinned; an existing pack version is never replaced. A verified local recovery copy is held independently of GitHub and the source model hosts. No private signing key is stored in this repository or a release asset. The signed pack and backup are ready; the 1.5.0 app remains subject to its separate native acceptance and release gates.
