# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.19`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.19/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.19/SHA256SUMS.txt)
- Size: 7,450,344 bytes
- SHA-256: `b3b14bcfbe07907e254c4b9c70e68991b7ce59e62e5233ba1f45da10137d879f`

Version `v1.14.19` allows manual Loop batches to run alongside VPS Agent jobs, with independent progress, logs and stop controls. Shared output-name reservations protect jobs targeting the same folder. Each side retains its own concurrency setting and shares VPS resources. No website migration is needed. See [release notes](releases/v1.14.19.md) and [image-upscale third-party notices](releases/v1.14.17.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X and Upscayl resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
