# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.20`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.20/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.20/SHA256SUMS.txt)
- Size: 7,519,906 bytes
- SHA-256: `64780555e2c96641e7f8c3cf0a75f3d4fa60224094294a6827218dfb8c79f99d`

Version `v1.14.20` adds the **Tải media** yt-dlp workspace with correct Vietnamese/Unicode titles and filenames, optional **FHD / 4K** downsizing after image AI upscale (default remains model-sized), and larger Flow image watermark recognition shared by image/video pipelines. Manual Loop/VPS Agent parallel operation is retained. No website migration is needed. See [release notes, verification and third-party notices](releases/v1.14.20.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
