# bearbar releases

bearbar is a lightweight widget dock that replaces the Windows taskbar.

This repository only hosts the installers and the update files. The source code lives elsewhere.

## Install

1. Open the [latest release](https://github.com/Glazeen/bearbar-releases/releases/latest).
2. Download `bearbar-setup-<version>.exe` and run it.

The installer isn't code-signed yet, so Windows SmartScreen may warn the first time. Choose
**More info › Run anyway**.

## Updates

Installed copies update themselves. bearbar checks for a new version a minute after it starts and
then every few hours, downloads it in the background, and installs it the next time it quits. To
update straight away, use **Restart to update** in the tray menu.

## Getting the Windows taskbar back

- Quitting bearbar brings the taskbar back.
- If it ever stays hidden, run **Restore Windows taskbar** from the Start menu.
- Uninstalling (Settings › Apps › bearbar) restores it too.

## The other files in a release

`latest.yml` and the `.blockmap` file are read by installed copies to find and download updates.
You don't need to download them.
