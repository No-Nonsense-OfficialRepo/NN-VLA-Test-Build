# NNVLA v1.0.11 Test Build

This is a Windows x64 development preview of the standalone No-Nonsense room UI.

- Borderless 320 px wide window, vertically resizable to show more room members.
- Host or Join room controls, passwords, room keys, roster, blocking, diagnostics, and profile editing.
- NNLL style profile picture crop, zoom, and pan. Name and picture changes propagate to connected peers.
- The compact crop dialog and 13 px checkbox indicators fit the 320 × 320 starting window.

The EXE is **not a complete fresh-PC installer**: the native VLA service and driver are not bundled. Automatic removal is disabled because this preview does not own the native service. It is unsigned, and a two-PC Host/Join test remains outstanding.

The packaged QML startup check passed. A local Microsoft Defender custom scan reported zero detections for this exact EXE with signature version `1.463.299.0`; the file hash and test record are in `validation.json`. This scan does not predict reputation or detection on other PCs.

Source and licence information: `README.md`, `SOURCE-PROVENANCE.md`, `THIRD_PARTY_NOTICES.md`, and `LICENSE` in the source archive.
