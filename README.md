# No-Nonsense Virtual LAN Adapter (NNVLA) — Test Builds

Portable Windows development test builds of No-Nonsense Virtual LAN Adapter.

## Download

[Download NNVLA v1.0.11 Test Build](https://github.com/No-Nonsense-OfficialRepo/NN-VLA-Test-Build/releases/tag/v1.0.11). Download the attached `NNVLA-v1.0.11-Test-Build-Windows-x64.zip`, extract it to a writable folder, then run `NN VLA V1.0.11.exe` inside the extracted `NN-VLA-v1.0.11-preview` folder. GitHub's automatically generated source ZIP is not the portable app.

## About this build

- Version: 1.0.11, Windows x64 development test build.
- Features: compact Host and Join UI, room keys, password and block controls, roster, diagnostics, and profile editing. See [release notes](RELEASE_NOTES.md).
- Limitation: the native VLA service and driver are not bundled. A fresh PC cannot set up tunnelling with this build; hosting or joining requires an already installed compatible service. Automatic VLA removal is disabled, and a two-PC test remains outstanding.
- Verification: packaged UI startup check passed. The unsigned EXE had zero detections in a local Defender custom scan at the recorded signature version; results on other PCs can differ.
- Integrity: compare the download with [SHA256SUMS.txt](SHA256SUMS.txt).
- Licensing: [GPL-3.0](LICENSE). The preview ZIP includes third-party notices and licence texts.

For source code, build instructions, or issues, visit [NN-VLA](https://github.com/No-Nonsense-OfficialRepo/NN-VLA).
