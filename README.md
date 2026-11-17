# Video Batch Tool — Releases

Windows (x64) downloads for **Video Batch Tool**: YouTube download, batch video editing, and AI subtitles.

## One-line install

In PowerShell (no administrator rights needed):

```powershell
irm https://github.com/albertyang-nv/VideoBatchTool-releases/releases/latest/download/install.ps1 | iex
```

Installs to `%LOCALAPPDATA%\Programs\VideoBatchTool`, adds Start Menu / Desktop shortcuts, and registers the app in Apps & features. Run it again to update, or use **Help > Check for Updates** inside the app (it also checks quietly at startup). Every download is verified against `SHA256SUMS.txt`.

Uninstall from Apps & features, or run the installer with `-Uninstall`.

## Manual download

Get `VideoBatchTool-v<version>-win64.exe` (or the `.zip`) from the [Releases](../../releases/latest) page.

FFmpeg, ffprobe and yt-dlp are not bundled; set their paths in Settings (`winget install Gyan.FFmpeg yt-dlp.yt-dlp`).

---

# Video Batch Tool — 下載

在 PowerShell 執行以下指令即可一鍵安裝，不需要系統管理員權限：

```powershell
irm https://github.com/albertyang-nv/VideoBatchTool-releases/releases/latest/download/install.ps1 | iex
```

再次執行即可更新，也可在程式內使用「說明 > 檢查更新」。
