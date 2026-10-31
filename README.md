# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.18`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.18/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.18/SHA256SUMS.txt)
- Size: 7,447,673 bytes
- SHA-256: `beeb8c1826582164a90666eab75c50211bab3786f425097b3838731fab790248`

Version `v1.14.18` adds a visible new-version notification with View update / Later actions, periodic checks while the app is visible and a 24-hour same-version reminder cooldown. Notifications do not steal focus or download/install automatically. Existing media processing and update integrity/safety checks are unchanged; no website migration is needed. See [release notes](releases/v1.14.18.md) and [image-upscale third-party notices](releases/v1.14.17.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X and Upscayl resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
