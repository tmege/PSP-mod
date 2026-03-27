# 2. Firmware Update

> **Note:** This step is only required if the PSP is running a firmware version below 6.60. If the PSP is already on 6.60 or 6.61, proceed directly to [ARK-4 Installation](03-ark4-installation.md).

## Locating the Firmware

The firmware update file is already included in this repository at [`ARK4(1)/UPDATE/`](../ARK4(1)/UPDATE/).

## Installation Procedure

### Preparing the Memory Card

1. Connect the PSP to the computer via USB
2. Create the following directory structure on the memory card:

```
ms0:/PSP/GAME/UPDATE/
```

3. **Copy** the `EBOOT.PBP` file from [`ARK4(1)/UPDATE/`](../ARK4(1)/UPDATE/) into the `UPDATE` directory on the memory card:

```
ms0:/PSP/GAME/UPDATE/EBOOT.PBP
```

5. Disconnect the USB cable

### Running the Update

1. Ensure the battery is at **80% or above** and that the **charger is connected**
2. On the PSP, navigate to **Game** > **Memory Stick**
3. An update icon will appear
4. Launch the application and follow the on-screen instructions
5. **Do not power off the PSP** during the update process
6. The PSP will restart automatically upon completion

### Verification

Navigate to **Settings** > **System Settings** > **System Information** to confirm that the firmware version now reads 6.60 or 6.61.
