# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.25`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.25/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.25/SHA256SUMS.txt)
- Size: 7,548,674 bytes
- SHA-256: `d4eae7d4b797c91be5949af700c5ab9166ff9e3f1139e5b626e7378ae9e65954`

Version `v1.14.25` adds **Xóa nền** for local PNG/JPEG background removal with a before/after preview and transparent PNG output. It recognizes mislabeled PNG/JPEG files by their contents. First-time setup requires Python 3.11–3.13 (64-bit); rembg and model files are downloaded on demand. See [release notes and verification](releases/v1.14.25.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
