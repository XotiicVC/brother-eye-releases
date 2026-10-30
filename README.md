# Brother Eye releases

This repository distributes **Brother Eye**, a personal AI-powered business headquarters for Windows. It contains releases and update files only; Brother Eye's source code is private.

## Installing

Download `BrotherEye_<version>_x64-setup.exe` from the [latest release](../../releases/latest) and run it. It installs for your Windows user only and adds Brother Eye to the Start menu.

The installer isn't code-signed yet, so Windows may show "Windows protected your PC". Click **More info → Run anyway**.

## Updates

Brother Eye checks this repository for a newer version **only when you click Check for updates** (Settings → About). Updates are installed only after you confirm. Each one is verified against Brother Eye's update-signing key before it's installed, and your data is never deleted by an update.

Each release contains:

- `BrotherEye_<version>_x64-setup.exe`: the installer
- `BrotherEye_<version>_x64-setup.exe.sig`: its update signature
- `latest.json`: the update description Brother Eye reads
