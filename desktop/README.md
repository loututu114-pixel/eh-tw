# EhViewer Desktop 0.1.0

Current public desktop release: `0.1.0`.

## Downloads

### macOS

- [EhViewer Desktop-0.1.0-universal-mac.zip](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-universal-mac.zip)
- [EhViewer Desktop-0.1.0-universal.dmg](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-universal.dmg)

### Windows

- [EhViewer Desktop-0.1.0-ia32-portable.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-ia32-portable.exe)
- [EhViewer Desktop-0.1.0-ia32-setup.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-ia32-setup.exe)
- [EhViewer Desktop-0.1.0-x64-portable.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-x64-portable.exe)
- [EhViewer Desktop-0.1.0-x64-setup.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.1.0/EhViewer%20Desktop-0.1.0-x64-setup.exe)

## Which File To Use

- macOS: `universal.dmg` is the normal installer.
- Windows 10/11 64-bit: `x64-setup.exe` is the normal installer.
- Windows 32-bit: `ia32-setup.exe` only if the system is actually 32-bit.
- `portable.exe` builds run without a normal install and are better for testing or removable storage.

## Quick Start

### macOS

1. Download `EhViewer Desktop-0.1.0-universal.dmg`.
2. Open the DMG and drag the app into `Applications`.
3. Launch the app.
4. If Gatekeeper blocks the first launch, open the app from Finder with `Open`.

### Windows

1. Download `EhViewer Desktop-0.1.0-x64-setup.exe` on normal 64-bit systems.
2. Run the installer and complete setup.
3. Launch EhViewer Desktop from the Start menu or desktop shortcut.
4. If you prefer no install, use the matching `portable.exe` build instead.

## Integrity

- `desktop/latest/SHA256SUMS.txt` contains the published checksums.
- `desktop/latest/desktop-update.json` is the updater payload consumed by the desktop client.
- `desktop/latest/LATEST.json` mirrors the latest updater payload for simple fetch flows.

## Updates

- The desktop updater selects the correct installer from the published artifact list.
- `desktop/latest/` always tracks the newest public release metadata.
- `desktop/releases/0.1.0/` stores the versioned notes and metadata for this release.
