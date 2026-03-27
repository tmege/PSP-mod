# 4. Reverting & Uninstalling ARK-4

> **Note:** For installation instructions (cIPL and Full Flash), refer to the main [ARK-4 Installation](03-ark4-installation.md) guide.

## Reverting cIPL to Temporary Mode

To remove the permanent installation and revert to temporary mode:

1. Launch the **ARK cIPL Flasher** again
2. Select the option to uninstall/restore the original IPL
3. The PSP will return to official firmware on the next reboot

Alternatively, reinstalling the official 6.61 firmware via the update method described in [Firmware Update](02-firmware-update.md) will also remove the cIPL.

## Uninstalling ARK-4

To fully remove ARK-4 from the PSP and restore stock firmware:

1. Delete the ARK-4 directories from the memory card (`ARK_01234`, `ARK_Loader`, `ARK_cIPL`, `ARK_Full_Installer`)
2. Delete the `SEPLUGINS` directory
3. If cIPL was installed: reinstall the official 6.61 firmware
4. The PSP will be running stock firmware
