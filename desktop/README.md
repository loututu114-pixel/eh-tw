# EhViewer Desktop 0.2.8

目前公開桌面版版本：`0.2.8`

本頁以繁體中文為主，並附上簡短 English summary。

## 推薦下載

| 平台 | 建議檔案 | 說明 |
| --- | --- | --- |
| macOS | `universal.dmg` | 一般安裝首選，適合大多數 Mac |
| Windows 10/11 64 位元 | `x64-setup.exe` | 一般安裝首選 |
| Windows 32 位元 | `ia32-setup.exe` | 僅在 32 位元系統上使用 |
| 免安裝需求 | `portable.exe` | 測試、隨身碟、免安裝使用 |

## 直接下載連結

| 平台 | 檔案 | 直接連結 |
| --- | --- | --- |
| macOS Universal | `EhViewer.Desktop-0.2.8-universal.dmg` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-universal.dmg> |
| Windows 64-bit Setup | `EhViewer.Desktop-0.2.8-x64-setup.exe` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-x64-setup.exe> |
| Windows 64-bit Portable | `EhViewer.Desktop-0.2.8-x64-portable.exe` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-x64-portable.exe> |
| Windows 32-bit Setup | `EhViewer.Desktop-0.2.8-ia32-setup.exe` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-ia32-setup.exe> |
| Windows 32-bit Portable | `EhViewer.Desktop-0.2.8-ia32-portable.exe` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-ia32-portable.exe> |
| macOS Universal | `EhViewer.Desktop-0.2.8-universal-mac.zip` | <https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-universal-mac.zip> |

## 下載

### macOS

- [EhViewer.Desktop-0.2.8-universal-mac.zip](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-universal-mac.zip)
- [EhViewer.Desktop-0.2.8-universal.dmg](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-universal.dmg)

### Windows

- [EhViewer.Desktop-0.2.8-ia32-portable.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-ia32-portable.exe)
- [EhViewer.Desktop-0.2.8-ia32-setup.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-ia32-setup.exe)
- [EhViewer.Desktop-0.2.8-x64-portable.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-x64-portable.exe)
- [EhViewer.Desktop-0.2.8-x64-setup.exe](https://github.com/loututu114-pixel/eh-tw/releases/download/desktop-v0.2.8/EhViewer.Desktop-0.2.8-x64-setup.exe)

## 版本選擇

- macOS：優先使用 `universal.dmg`，一般安裝最直覺。
- Windows 10/11 64 位元：優先使用 `x64-setup.exe`。
- Windows 32 位元：僅在真正的 32 位元系統上使用 `ia32-setup.exe`。
- `portable.exe` 適合免安裝使用、外接硬碟或快速測試。

## 功能重點

| 模組 | 說明 |
| --- | --- |
| 畫冊流 | 提供首頁畫冊瀏覽、結果列表與快速進入 |
| 資料頁 | 集中顯示畫冊資訊、標籤與閱讀入口 |
| 閱讀頁 | 以桌面漫畫閱讀為核心，提供主要閱讀節奏 |
| 更新通道 | 提供公開版本、更新描述檔與校驗資訊 |

- 以桌面漫畫閱讀為核心，提供首頁畫冊流、資料頁、閱讀頁三段式體驗。
- 支援畫冊列表瀏覽、下載安裝、版本化更新與公開釋出資訊。
- 支援本地快取、更新描述檔、校驗檔與版本化釋出資訊。
- 公開說明與下載資訊以繁體中文為主，方便台灣與繁中使用者直接理解。

## 系統建議

- macOS：建議使用較新的 Apple Silicon 或 Intel Mac，下載對應 DMG 版本即可。
- Windows：建議優先使用 64 位元 Windows 10/11。
- 若只想快速體驗，可直接下載 `portable.exe`。

## 發佈通道

- `Releases`：提供一般使用者直接下載的安裝包。
- `desktop/latest/`：提供桌面端更新程式讀取的最新描述檔。
- `desktop/releases/<version>/`：提供版本化釋出說明與對應校驗資訊。

## 快速開始

### macOS

1. 下載 `EhViewer.Desktop-0.2.8-universal.dmg`。
2. 開啟映像檔後把 App 拖進 `Applications`。
3. 第一次啟動若被 Gatekeeper 攔住，請在 Finder 右鍵選 `Open`。

### Windows

1. 下載 `EhViewer.Desktop-0.2.8-x64-setup.exe`。
2. 執行安裝程式並完成安裝。
3. 若不想安裝，可改用對應架構的 `portable.exe`。


## 更新與校驗

- `desktop/latest/SHA256SUMS.txt`：公開校驗值。
- `desktop/latest/desktop-update.json`：桌面端更新描述檔。
- `desktop/latest/LATEST.json`：供簡單更新流程讀取的最新版本描述。

## 常見問題

- 想正常安裝：macOS 用 `universal.dmg`，Windows 用 `x64-setup.exe`。
- 不想安裝：直接使用 `portable.exe`。
- 想確認檔案是否正確：比對 `SHA256SUMS.txt`。
- 想知道目前最新版本：查看 `desktop/latest/version.txt`。

## English Summary

- Traditional Chinese is the primary public language for this project.
- macOS users should start with `universal.dmg`.
- Windows users should start with `x64-setup.exe`.
- Portable Windows builds are available if you do not want a normal installer.
- Update metadata and checksums are published under `desktop/latest/`.

