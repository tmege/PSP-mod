# 8. Troubleshooting

## Common Issues

### The PSP Does Not Boot / Black Screen

1. Hold the **Power** button for 10 seconds to force a shutdown
2. Remove the battery, wait 10 seconds, then reinsert it
3. Boot while holding **R** to access the Recovery menu
4. In Recovery, disable all plugins and restart

### ARK-4 Fails to Launch

- Verify that the files have been copied to the correct locations on the memory card
- Confirm that the firmware version is 6.60 or 6.61
- Re-download ARK-4 and repeat the file transfer

### A Plugin Causes a Crash

1. Boot while holding **R** to access the Recovery menu
2. Navigate to **Plugins** and disable the offending plugin
3. Restart the PSP
4. Remove the plugin file (`.prx`) and its corresponding entry in the configuration file

### ISO Games Do Not Appear

- Verify that the files are located in `ms0:/ISO/`
- Confirm the file extension is `.iso` or `.cso`
- Restart the PSP

### Error "The game could not be started" (80010087)

- The ISO file may be corrupted — re-download or re-dump it
- Attempt converting to CSO and then back to ISO

### Memory Card Not Detected

- Clean the contacts on the memory card and the PSP's card slot
- If using a micro SD adapter, ensure the SD card is properly seated
- Test with a different memory card if available

## Full Reset

To restore the PSP to its original, unmodified state:

1. Delete the ARK-4 directories from the memory card
2. Delete the `SEPLUGINS` directory
3. If cIPL was installed: reinstall the official 6.61 firmware
4. The PSP will be running stock firmware
