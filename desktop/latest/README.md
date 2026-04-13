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

## Integrity

- `desktop/latest/SHA256SUMS.txt` contains the published checksums.
- `desktop/latest/desktop-update.json` is the updater payload consumed by the desktop client.
- `desktop/latest/LATEST.json` mirrors the latest updater payload for simple fetch flows.

## Notes

- macOS releases currently include `arm64` and `universal` builds.
- Windows releases are published from GitHub Actions running on Windows hosts.
- The desktop app updater chooses the correct installer by platform and architecture from the published artifact list.

