# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.24`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.24/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.24/SHA256SUMS.txt)
- Size: 7,524,417 bytes
- SHA-256: `1e9797b4a6cabb5386a2388cdb144fd80c0c1c72884dcd8ac252ba7668764626`

Version `v1.14.24` allows both exact Vota origins (`https://vota.work` and `https://www.vota.work`) in the local bridge CORS allowlist. This fixes browser requests from the apex domain without allowing arbitrary origins. AI models and inference behavior are unchanged. See [release notes and verification](releases/v1.14.24.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
