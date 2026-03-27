# 3. ARK-4 Installation

This procedure installs ARK-4 as a **temporary** custom firmware. In temporary mode, the CFW must be re-launched from the XMB after each reboot. To make it permanent, refer to [Permanent Installation](04-ark4-permanent.md).

## Step 1: Download ARK-4

1. Download the latest release: [ARK4.zip](https://github.com/PSP-Archive/ARK-4/releases/latest/download/ARK4.zip)
2. Extract the archive on your computer

## Step 2: Copy Files to the Memory Card

1. Connect the PSP to the computer via USB
2. On the PSP: **Settings** > **USB Connection** to enable USB mode
3. Copy the following directories from the extracted archive to the memory card:

| Source Directory | Destination on Memory Card |
| ---------------- | ------------------------- |
| `ARK_01234/` | `ms0:/PSP/SAVEDATA/ARK_01234/` |
| `ARK_Loader/` | `ms0:/PSP/GAME/ARK_Loader/` |

The resulting directory structure should be:

```
ms0:/
├── PSP/
│   ├── GAME/
│   │   └── ARK_Loader/
│   │       └── EBOOT.PBP
│   └── SAVEDATA/
│       └── ARK_01234/
│           ├── ARK.BIN
│           ├── ARK4.BIN
│           └── ...
└── SEPLUGINS/
    ├── game.txt
    ├── vsh.txt
    └── pops.txt
```

4. Disconnect the USB cable

## Step 3: Launch ARK-4

1. On the PSP, navigate to **Game** > **Memory Stick**
2. Select and launch **ARK Loader**
3. The screen may briefly flash — this is normal behaviour
4. The XMB will reappear with ARK-4 active

## Step 4: Verify the Installation

1. Navigate to **Settings** > **System Settings** > **System Information**
2. The firmware version should display **ARK 4.xx.xx Live** (or similar)

If the version string includes "ARK", the installation was successful.

## Important Notes

- In temporary mode, ARK-4 must be re-launched via the ARK Loader each time the PSP is restarted
- This mode is entirely safe and easily reversible — simply restarting the PSP without launching the loader will revert to the official firmware
- To make ARK-4 load automatically at boot, proceed to [Permanent Installation](04-ark4-permanent.md)
