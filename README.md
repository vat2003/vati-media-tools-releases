# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.17`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.17/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.17/SHA256SUMS.txt)
- Size: 7,447,066 bytes
- SHA-256: `137507f2b68c80bd67cc25a171c976900b8812122b7364c0c4977b6656730e6a`

Version `v1.14.17` adds image upscaling via the external Upscayl Vulkan CLI, native-image before/after comparison, and user-approved engine/seven-model downloads with individual or bulk download/delete. Fixes settings overflow, TTA checkbox alignment and run/output buttons. Existing VPS Loop and Video2X behavior is unchanged; no website migration is needed. See [release notes and third-party notices](releases/v1.14.17.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X and Upscayl resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
