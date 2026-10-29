# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.13`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.13/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.13/SHA256SUMS.txt)
- Size: 7,384,655 bytes
- SHA-256: `cfe080b11114ddbf8814ae4903d905bf642a3c6f9d8fa89db31a2e57b191bf6b`

Version `v1.14.13` improves Flow-logo contour restoration on native 720p video, processes recognized Flow clips through their final frame automatically, and adds filtered/all bulk retries plus confirmed file deletion. Alpha-first, glyph-local guarded AI avoids replacing a whole square of background. Some frames still need visual review; this is not a guarantee of artifact-free reconstruction. See [release notes](releases/v1.14.13.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes and Video2X resources download only when requested; they are not bundled. Source code, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
