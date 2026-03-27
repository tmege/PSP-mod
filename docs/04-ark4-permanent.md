# 4. Making ARK-4 Permanent (cIPL)

> **Prerequisite:** ARK-4 must be running in temporary mode before proceeding. Complete [ARK-4 Installation](03-ark4-installation.md) first.

The cIPL (custom Initial Program Loader) method writes ARK-4 to the PSP's internal flash memory, allowing it to load automatically at every boot without the need to manually launch the loader.

## Installation Procedure

### Step 1: Copy the cIPL Flasher

1. Connect the PSP to the computer via USB
2. From the ARK-4 archive, locate the `ARK_cIPL/` directory
3. Copy `ARK_cIPL/` into `ms0:/PSP/GAME/`:

```
ms0:/PSP/GAME/ARK_cIPL/
└── EBOOT.PBP
```

4. Disconnect the USB cable

### Step 2: Flash cIPL

1. Ensure ARK-4 is currently active (launch the ARK Loader if it is not)
2. Navigate to **Game** > **Memory Stick**
3. Launch **ARK cIPL Flasher**
4. Press **X** to confirm and begin flashing
5. **Do not power off the PSP** during this process
6. The PSP will restart automatically once the process is complete

### Step 3: Verify

After rebooting, navigate to **Settings** > **System Settings** > **System Information**. The firmware version should display the ARK-4 version string, confirming that the CFW is now loading permanently.

## Reverting to Temporary Mode

To remove the permanent installation and revert to temporary mode:

1. Launch the **ARK cIPL Flasher** again
2. Select the option to uninstall/restore the original IPL
3. The PSP will return to official firmware on the next reboot

Alternatively, reinstalling the official 6.61 firmware via the update method described in [Firmware Update](02-firmware-update.md) will also remove the cIPL.

## Caution

Flashing the IPL carries a small but non-zero risk of bricking the PSP if the process is interrupted (e.g., by a power loss). Ensure the battery is adequately charged and the charger is connected before proceeding.
