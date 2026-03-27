# PSP 3000 — Modding Guide with ARK-4

A comprehensive step-by-step guide to modding a PSP 3000 using the **ARK-4** custom firmware.

This guide is based on the method demonstrated in [this video tutorial](https://www.youtube.com/watch?v=zKD__94GxWQ).

![PSP 3000 with custom transparent blue shell running ARK-4](assets/IMG_3068.jpeg)

## Overview

| Detail           | Value              |
| ---------------- | ------------------ |
| Console          | PSP 3000           |
| Official FW      | 6.61               |
| Custom Firmware  | ARK-4              |
| Status           | Fully operational  |

## Table of Contents

1. [Prerequisites](docs/01-prerequisites.md) — Required hardware and software
2. [Firmware Update](docs/02-firmware-update.md) — Upgrading to 6.60/6.61 (if needed)
3. [ARK-4 Installation](docs/03-ark4-installation.md) — Temporary, cIPL, and Full Flash installation
4. [Reverting & Uninstalling](docs/04-ark4-permanent.md) — Reverting cIPL and removing ARK-4
5. [Configuration](docs/05-configuration.md) — Post-installation settings
6. [Plugins](docs/06-plugins.md) — Installed plugins and their configuration
7. [Homebrews and Emulators](docs/07-homebrews.md) — Homebrew applications
8. [Troubleshooting](docs/08-troubleshooting.md) — Common issues and solutions
9. [Hardware Modification](docs/09-hardware-mod.md) — Shell swap and physical customisation

## What is ARK-4?

[ARK-4](https://github.com/PSP-Archive/ARK-4) is an open-source custom firmware for the PlayStation Portable. It enables the following capabilities:

- Running homebrew applications and emulators
- Installing system plugins
- Customising the XMB interface (themes, icons)
- Loading game backups in ISO/CSO format

ARK-4 is actively maintained and supports all PSP models (1000, 2000, 3000, Go, and Street).

## Included Files

All files required for the modding process are included in the [`ARK4(1)/`](ARK4(1)/) directory:

| Resource | Location |
| -------- | -------- |
| ARK-4 custom firmware | [`ARK4(1)/`](ARK4(1)/) |
| ARK Loader | [`ARK4(1)/ARK_Loader/`](ARK4(1)/ARK_Loader/) |
| ARK savedata | [`ARK4(1)/ARK_01234/`](ARK4(1)/ARK_01234/) |
| cIPL Flasher | [`ARK4(1)/PSP/ARK_cIPL/`](ARK4(1)/PSP/ARK_cIPL/) |
| Firmware update (6.61) | [`ARK4(1)/UPDATE/`](ARK4(1)/UPDATE/) |
| Themes | [`ARK4(1)/themes/`](ARK4(1)/themes/) |
| PC utilities | [`ARK4(1)/PC/`](ARK4(1)/PC/) |

## Useful Links

| Resource | Link |
| -------- | ---- |
| Video tutorial | [YouTube](https://www.youtube.com/watch?v=zKD__94GxWQ) |
| ARK-4 GitHub repository | [PSP-Archive/ARK-4](https://github.com/PSP-Archive/ARK-4) |

## Hardware Used

| Item | Link |
| ---- | ---- |
| Micro SD to Memory Stick Pro Duo adapter | [Amazon](https://amzn.to/439xPEv) |
| Micro SD card | [Amazon](https://amzn.to/44rR8v8) |
| Custom transparent blue replacement shell with buttons | AliExpress |

## Disclaimer

This guide documents a personal experience. Console modification carries inherent risks, including the possibility of bricking the device. Proceed with caution and at your own risk.
