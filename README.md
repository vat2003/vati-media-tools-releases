# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.23`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.23/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.23/SHA256SUMS.txt)
- Size: 7,524,602 bytes
- SHA-256: `ea9b44f72f5f53020d9c4086d94071af776f46d1658238fd72232b25d424e164`

Version `v1.14.23` explicitly warns when requested AI accepted no patches and the output remains alpha-only, even when residual diagnostics are zero. It prioritizes preserving original detail; **this is not a claim of cleaner FHD removal**. Native restoration and AI acceptance limits, models and VPS Agent behavior are unchanged. Only use fixed-logo mode for original, uncropped/unscaled Flow HD/FHD clips containing a logo. The web companion adds guarded glyph-local FHD AI; GitHub source publication is separate from production website deployment. See [release notes and verification](releases/v1.14.23.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
