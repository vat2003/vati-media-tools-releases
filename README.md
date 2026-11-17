# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.22`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.22/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.22/SHA256SUMS.txt)
- Size: 7,524,389 bytes
- SHA-256: `1433318c101d83f8fa066e78f5789c8907fef071228784a9ec67a2ddbb0b639e`

Version `v1.14.22` processes original Flow HD/FHD video using one fixed logo region on every frame, without rejecting textured backgrounds on detector confidence. Only use this mode for original, uncropped/unscaled Flow clips containing a logo. Other dimensions and images retain detection. The web companion adds an explicit fixed-profile mode; its GitHub source publication is separate from the operator's production website deployment. VPS Agent behavior is unchanged. See [release notes and verification](releases/v1.14.22.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes, Video2X, Upscayl, yt-dlp and Deno resources download only when requested; they are not bundled. Upscayl-NCNN is an independent, unmodified AGPL-3.0 program with source/license links in the app; its LICENSE/README are retained on download. yt-dlp source is Unlicense, but its bundled Windows executable includes GPLv3+ code; Deno is MIT. Only download media you are authorized to download. Flow reconstruction still needs visual review (31/46 tested images retain residual warnings). Source code of VATI, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
