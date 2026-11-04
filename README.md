# 核醫排程工作站 NM-Schedule

Windows Portable 核醫排程工作站的正式發行下載區，提供版本說明、完整程式包與更新資訊。

**[下載最新正式版](https://github.com/purekboy-ui/nm-schedule-releases/releases/latest)** — 不需登入 GitHub 或 Google 帳號。

## 下載與使用

1. 開啟最新 Release，在 Assets 下載 `NM-Schedule-v版本-portable.zip`。請勿下載 GitHub 自動產生的 Source code 壓縮檔當作程式。
2. 將 ZIP 完整解壓縮到您可寫入的資料夾，開啟 `nm-schedule.exe`。不要直接在 ZIP 中執行。
3. 醫院電腦的軟體執行、防毒與網路政策仍依資訊室規定。

## 從舊版更新

程式採半自動更新：檢查版本及顯示說明，再以預設瀏覽器開啟這裡，由使用者下載與更換程式。不使用 PowerShell 或自動替換更新器。

1. 在舊程式先儲存並確認備份完成，記下「軟體更新」顯示的實際資料位置，再關閉程式。
2. 保留整份舊程式資料夾，將新版解壓縮至另一個資料夾。
3. 若原資料位於舊程式旁，將完整 `data` 資料夾複製到新版程式旁；若原資料位於 Windows 使用者資料夾，保留原位置並使用相同 Windows 帳號。
4. 開啟新版，確認版本、排程與歷史資料完整後，再停用舊版。不要同時開新舊版操作同一份資料。

本 repo 只提供正式發行檔與說明，不含病人或工作資料。原始碼備份另行管理。

## 檔案完整性與版本檢查

每個 Release 附 Portable ZIP 與 `SHA256SUMS.txt`，便於核對下載完整性。`latest.json` 與 `latest.json.sig` 供程式使用既有 RSA 公鑰驗證版本資訊。雜湊或版本資訊簽章不等於 Windows Authenticode 簽章，也不保證防毒允許執行。

正式入口固定為 `/releases/latest`；後續版本沿用同一入口。
