# 5. Configuration

## ARK-4 Recovery Menu

The Recovery menu provides access to advanced ARK-4 settings.

**Access:** Hold **R** during boot.

### Key Options

| Option              | Description                                         |
| ------------------- | --------------------------------------------------- |
| Toggle USB          | Enable or disable USB access from Recovery          |
| Toggle Plugins      | Enable or disable installed plugins                 |
| CPU Speed           | Adjust the processor clock speed (222/333 MHz)      |
| XMB Settings        | Customise XMB behaviour                             |
| Advanced Settings   | Advanced CFW parameters                             |

## CPU Clock Speed

- **222 MHz**: Default speed; conserves battery life and is sufficient for most PSP games
- **333 MHz**: Maximum performance; recommended for emulators and demanding homebrew applications

This setting is accessible via **Recovery** > **CPU Speed**.

## SEPLUGINS Directory

The `ms0:/SEPLUGINS/` directory contains plugin configuration files:

| File         | Execution Context                                     |
| ------------ | ----------------------------------------------------- |
| `game.txt`   | Plugins loaded during PSP game execution              |
| `vsh.txt`    | Plugins loaded in the XMB (Visual Shell)              |
| `pops.txt`   | Plugins loaded during PS1 game execution              |

Each file uses the following format — one plugin per line, followed by `1` (enabled) or `0` (disabled):

```
ms0:/SEPLUGINS/plugin_name.prx 1
ms0:/SEPLUGINS/another_plugin.prx 0
```

## Recommended Settings

- **USB Charging**: Enable in System Settings to allow charging via USB
- **Auto Sleep**: Consider disabling during extended emulation sessions
