# VATI Media Tools Releases

Public GitHub Releases repository for VATI Media Tools installers.

## Latest Release

- Version: `v1.14.16`
- Platform: Windows AMD64
- Installer: [vati-media-tools-amd64-installer.exe](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.16/vati-media-tools-amd64-installer.exe)
- Checksum: [SHA256SUMS.txt](https://github.com/vat2003/vati-media-tools-releases/releases/download/v1.14.16/SHA256SUMS.txt)
- Size: 7,413,054 bytes
- SHA-256: `7071ffa237afcbeb58335dfe073a25bafedb2429989ca09899376ba60bf19e6f`

Version `v1.14.16` saves VPS Loop output directly in the selected destination, without automatically creating a job-ID subfolder. Shared output-name reservations prevent parallel jobs from overwriting each other's files; existing outputs and folders remain untouched. No website migration is needed; update the Tool and restart the VPS agent. See [release notes](releases/v1.14.16.md).

Close the previous app and stop active batches/agents before installing. Reprocess original media, not an already damaged output. AI models, runtimes and Video2X resources download only when requested; they are not bundled. Source code, credentials, configuration and user test media are not published in this repository.

Installers are stored as assets under [GitHub Releases](https://github.com/vat2003/vati-media-tools-releases/releases), not in the source tree of this public repository.
