# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.21`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.21/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.21/SHA256SUMS.txt)
- Size: 7,522,701 bytes
- SHA-256: `479956aba15b15b24fa2e09dc8dcdf7daec58bc04f25c77ba1551d9d984e263d`

Version `v1.14.21` optimizes VPS Agent heartbeat and idle claims, negotiates 15-second progress reports and renews short-lived Realtime JWTs on the existing connection. Old-server/network fallback remains. The companion efficient-sync migration/server is required for full benefits; it has already been deployed by the operator. Media features from v1.14.20 remain. See [release notes and verification](releases/v1.14.21.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
