> [简体中文](../README.md) | [English](README.en.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

# AutoX CAN

> A Windows desktop tool for CAN / CAN FD log analysis. Import a log and a protocol definition, select signals, and generate an interactive HTML analysis report that can be shared and opened offline.

[**Download Windows V1.1.0**](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.1.0/AutoX_CAN_Setup_1.1.0.exe) · [All releases](https://github.com/hsj521/AutoX-CAN-Releases/releases)

## Why AutoX CAN

- **Fully local processing**: logs, protocol files, and reports stay on your computer. The application starts no service, uploads no data, and makes no network requests.
- **Common automotive log formats**: reads Vector ASC and BLF logs, including classic CAN and common CAN FD logs.
- **Protocol-based decoding**: reads DBC or XLSX definitions and decodes raw frames into engineering signal values.
- **Multi-channel replay**: select CAN channels 1–8 to prevent frames with the same CAN ID from different channels being decoded together.
- **Built for joint analysis**: each selected signal has its own colored Y-axis, making it easier to compare values with different units and ranges.

## Analyze a log in three steps

1. Import a `.dbc` / `.xlsx` protocol definition and an `.asc` / `.blf` CAN log.
2. Select the replay channel, then search for and add the signals to analyze.
3. Generate one self-contained HTML report. Zoom, pan, inspect values, or share it for offline viewing in a browser.

## Key features

| Feature | Description |
| --- | --- |
| ASC / BLF analysis | Reads ASC and BLF logs and converts between the two formats locally. |
| DBC / XLSX decoding | Supports Intel / Motorola byte order, signed values, scaling, offsets, and basic multiplexed signals. |
| Signal search | Search by signal name, message name, or CAN ID; analyze multiple signals together. |
| Interactive reports | HTML reports support zooming, panning, shared hover values, time-range selection, and Y-axis adjustment. |
| Two-point measurement | Select two samples to compare their time interval and, for the same signal, their value difference. |
| Windows desktop UI | Dark, high-DPI interface with F11 full screen and Esc to exit full screen. |

## Download and install

Current stable version: **V1.1.0**

1. Download [`AutoX_CAN_Setup_1.1.0.exe`](https://github.com/hsj521/AutoX-CAN-Releases/releases/download/v1.1.0/AutoX_CAN_Setup_1.1.0.exe).
2. Double-click the installer and follow the setup wizard.
3. Launch AutoX CAN from the Start menu or desktop shortcut after installation.

The SHA256 checksum and release notes are available on the [V1.1.0 Release page](https://github.com/hsj521/AutoX-CAN-Releases/releases/tag/v1.1.0).

## Feedback

For installation or usage issues, please open an [Issue](https://github.com/hsj521/AutoX-CAN-Releases/issues) with the AutoX CAN version, Windows version, and steps to reproduce.

---

This repository distributes installers, release notes, and checksums only. **It does not contain the AutoX CAN source code.**