# 3. ARK-4 Installation

This guide covers three installation methods: temporary, permanent (cIPL), and full flash. Start with the temporary installation, then optionally proceed to cIPL and/or full flash.

---

## Temporary Installation

1. All ARK-4 files are already included in this repository at [`ARK4(1)/`](../ARK4(1)/).
2. Plug your PSP into a computer. This will automatically enable USB Mode and mount the console's memory card to the computer. You can also plug the memory card directly into a computer if you have a Memory Stick compatible card reader.
   - If the console's USB mode doesn't automatically activate, it can be manually activated in the XMB settings.
3. Copy the contents from the [`ARK4(1)/`](../ARK4(1)/) folder to the memory card:
   - Copy the [`ARK_01234/`](../ARK4(1)/ARK_01234/) folder to `PSP/SAVEDATA/` on the PSP's memory card or PSP Go's internal storage.
   - Copy the [`ARK_Loader/`](../ARK4(1)/ARK_Loader/) folder to `PSP/GAME/` on the console's memory card.
     - You can also copy the [`ARK_Full_Installer/`](../ARK4(1)/PSP/ARK_Full_Installer/) and [`ARK_cIPL/`](../ARK4(1)/PSP/ARK_cIPL/) folders to the same `PSP/GAME/` folder to do a full flash or installation of permanent CFW respectively.
4. Exit USB mode after transferring the files over. View your games list and there should be a new listing for the ARK Loader, alongside its respective save file in the save data management.
5. To install custom firmware, select the **ARK Loader** application and launch it.
6. Once the PSP restarts, check in **Settings** > **System Settings** > **System Information** and confirm you see the system software version along with the custom firmware version after it.
7. Your PSP is now running temporary custom firmware. If you would like to install it permanently, continue to the section below for cIPL installation.

---

## Installing CFW with cIPL (Optional, recommended)

This is the preferred method of installing CFW, as it can run during bootup and can give you brick protection.

1. All ARK-4 files are already included in this repository at [`ARK4(1)/`](../ARK4(1)/).
2. Plug your PSP into a computer. This will automatically enable USB Mode and mount the console's memory card to the computer. You can also plug the memory card directly into a computer if you have a Memory Stick compatible card reader.
   - If the console's USB mode doesn't automatically activate, it can be manually activated in the XMB settings.
3. Copy the [`ARK_cIPL/`](../ARK4(1)/PSP/ARK_cIPL/) folder into `PSP/GAME/` on the memory card if you haven't done so already.
4. Launch the **ARK cIPL installer** application, and select the option for **New cIPL**.
5. Your PSP will now have cIPL ARK-4 CFW. It can be seen in the system settings.

> **Caution:** Flashing the IPL carries a small but non-zero risk of bricking the PSP if the process is interrupted. Ensure the battery is adequately charged and the charger is connected before proceeding.

---

## Full Flash Installation (Optional, recommended)

Normally, many functions of ARK-4 are kept in the `ARK_01234` save data folder, such as the CFW settings or custom launcher. If this is undesirable for you, you can install these functions to the PSP's internal flash memory so ARK-4's save data file is no longer necessary. That being said, the `ARK_01234` save file folder will still be prioritised for CFW settings if it's detected on the memory stick. It will also be re-created if you run an ARK-4 update from an OTA update or sideloading the ARK_Updater application.

Since the PSP's flash memory is also too small (except on the PSP Go) to store the custom launcher that comes with ARK-4's save data folder, PRO Shell will instead be used as the custom launcher with a separate and more basic recovery menu if the save data folder is not detected.

> **Note:** If you are using ARK-4 on a PSP Go, then the full flash installation can be skipped entirely, as you can just use the `ARK_01234` save file in the 16 GB internal memory.

1. All ARK-4 files are already included in this repository at [`ARK4(1)/`](../ARK4(1)/).
2. Plug your PSP into a computer. This will automatically enable USB Mode and mount the console's memory card to the computer. You can also plug the memory card directly into a computer if you have a Memory Stick compatible card reader.
   - If the console's USB mode doesn't automatically activate, it can be manually activated in the XMB settings.
3. Copy the [`ARK_Full_Installer/`](../ARK4(1)/PSP/ARK_Full_Installer/) folder into `PSP/GAME/` on the memory card.
4. Launch the application and follow the on-screen instructions.
5. Your PSP will now have ARK-4 fully installed on the console's internal flash memory, allowing the reliance on having an ARK-4 save file to be no longer necessary for operation.

---

## Verification

Go to **Settings** > **System Settings** > **System Information**. System Software should display **6.61 ARK-4**.

## Post-Jailbreak Tips

- **Installing Games:** Connect to PC and create a folder named `ISO` in the root of the Memory Stick. Place your `.ISO` or `.CSO` game files there.
- **Accessing the VSH Menu:** Press the **SELECT** button on the home screen to access the VSH menu and customise settings.
