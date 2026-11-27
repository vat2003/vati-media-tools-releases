# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.26`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.26/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.26/SHA256SUMS.txt)
- Size: 7,640,858 bytes
- SHA-256: `cbff8068c246da0b5e20349e5c05c06e2dec66da5420d2794f69db8f8cabf17f`

Version `v1.14.26` adds **Transcript** for transcription and subtitle export, **TTS** for narration and SRT/VTT dubbing, and automatic retries for intermittent TikTok webpage 403 errors in **Tải media**. See the [release notes](releases/v1.14.26.md) for supported engines and setup.

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
