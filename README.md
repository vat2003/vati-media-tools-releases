# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.14`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.14/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.14/SHA256SUMS.txt)
- Size: 7,387,626 bytes
- SHA-256: `67f44d6bb6b13764f427ff3d65e3d391f35bc8d90d88d7cb74604c3f721fe5e2`

Version `v1.14.14` fixes immediate VPS Loop failures on transient Transfer.it/MEGA metadata EOF/network errors with bounded read-only POST retries, backoff, Retry-After and cancellation. Permanent access/quota errors still fail; worker/Range/FFmpeg behavior is unchanged. Verified with a local disconnect simulation, not a guarantee for persistent service/network failure on a live VPS. See [release notes](releases/v1.14.14.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes and Video2X resources download only when requested; they are not bundled. Source code, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
