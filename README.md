# Ghostwriter — Downloads

Official installers for **Salai - Ghostwriter**, the AI-assisted writing app.

## Download

**[Get the latest release](https://github.com/SalaiApp/ghostwriter-releases/releases/latest)**

Pick the file for your platform from that release's **Assets**:

| Platform | File | Notes |
|---|---|---|
| **Windows** (64-bit) | `ghostwriter_<version>_win_x64_setup.exe` | Installs per-user; no admin rights needed. |
| **macOS** (Apple Silicon) | `ghostwriter_<version>_macos_arm64.dmg` | Requires macOS 12 (Monterey) or later on an M-series Mac. |

## Install

### Windows

1. Download `ghostwriter_<version>_win_x64_setup.exe`.
2. Run it. It installs for the current user and adds a Start-menu shortcut and an uninstaller.
3. Launch **Ghostwriter** from the Start menu or desktop shortcut.

If SmartScreen shows a "Windows protected your PC" prompt, click **More info → Run anyway** (the
build isn't code-signed yet).

### macOS

1. Download `ghostwriter_<version>_macos_arm64.dmg` and open it.
2. Drag **Ghostwriter** into the **Applications** folder.
3. **First launch — clear Gatekeeper.** The app isn't notarized yet, so a normal double-click is
   blocked with *"Ghostwriter can't be opened because Apple cannot check it for malicious
   software."* To allow it:
   - **Right-click** (or Control-click) **Ghostwriter in Applications → Open**, then confirm **Open**
     in the dialog. You only need to do this once; afterwards it opens normally.
   - If that option doesn't appear, open **Terminal** and run:
     ```bash
     xattr -dr com.apple.quarantine /Applications/Ghostwriter.app
     ```
     then open the app as usual.

## Updates

Ghostwriter checks this repository for a newer release on launch (and any time from
**Help → Check for Updates**):

- **Windows** — when an update is available, choosing **Update now** downloads and installs it and
  restarts the app for you. It will offer to save any unsaved work before restarting.
- **macOS** — the app notifies you and opens this releases page so you can download the new `.dmg`
  and reinstall.

## Support

Found a problem? You can send a report from inside the app via **Help → Report a Problem**.

<!-- Maintainer: add issue tracker / contact / privacy links here as they become available. -->
