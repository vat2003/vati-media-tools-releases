# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.15`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.15/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.15/SHA256SUMS.txt)
- Size: 7,411,929 bytes
- SHA-256: `d9d07e90cefb39c1097acaa1efa12460df7ae95556e7997334e2c19893bf73a9`

Version `v1.14.15` adds two independent VPS Loop job slots, automatic capacity-aware drive selection, and agent/web drive exclusions for cache and output. Canceling one job does not stop the other. Update the companion website/API and restart the agent on the VPS; existing tokens remain valid. Automatic selection does not enable old-file deletion. See [release notes](releases/v1.14.15.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes and Video2X resources download only when requested; they are not bundled. Source code, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
