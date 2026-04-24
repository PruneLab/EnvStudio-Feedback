# EnvStudio 使用者回饋

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.ja.md">日本語</a>
  |
  <a href="README.de.md">Deutsch</a>
  |
  <a href="README.fr.md">Français</a>
  |
  <a href="README.es.md">Español</a>
  |
  <a href="README.pt.md">Português</a>
  |
  <a href="README.ru.md">Русский</a>
  |
  <a href="README.ko.md">한국어</a>
</p>

## 關於 EnvStudio

**EnvStudio** 是一款現代化的 Windows 環境變數管理工具，基於 WinUI 3 原生構建。它替代了那個 20 年幾乎沒有變過的「系統內容 → 環境變數」對話方塊，為環境變數管理帶來了原生的 Windows 11 體驗。

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/zh-tw/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/zh-tw/cover2.png" width="48%" />
</p>

## 下載

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## 核心功能

- **直覺的視覺化編輯器** — 透過現代化的 WinUI 3 介面，輕鬆新增、編輯、刪除和重排環境變數。
- **PATH 列表管理** — 拖曳排序、去重偵測、死鏈偵測，PATH 項目管理從未如此簡單。
- **EXE 覆蓋偵測** — 掃描 PATH 中所有目錄的可執行檔，展示被覆蓋的程式，一鍵跳轉到衝突項。
- **作用域衝突偵測** — 使用者變數覆蓋同名系統變數時顯示刪除線和警告圖示，一眼看清目前生效的值。
- **非破壞性開關** — 停用變數而不刪除，隨時一鍵恢復，告別「刪了怕找不回來」的焦慮。
- **刪除安全檢查** — 刪除前自動掃描其他變數中的 `%VARNAME%` 引用，防止級聯故障。
- **變數展開預覽** — 滑鼠懸停在 `%VAR%` 引用上即可看到完整解析路徑。
- **外部變更偵測** — 即時監控登錄檔，其他程式修改環境變數時立即提醒重新整理。
- **設定檔切換** — 為不同開發環境儲存命名設定檔（如「Java 8」「Node.js」「AI/ML」），側欄一鍵切換。
- **快照與回滾** — 每次儲存自動建立快照，Git 風格的差異對比，一鍵回滾到任意歷史版本。
- **搜尋與篩選** — 支援正規表示式，符合的 PATH 子項自動展開並顯示符合數量。
- **匯出指令碼** — 一鍵匯出為 `.ps1`、`.bat` 或 `.env` 檔案，方便團隊共享或系統重灌後恢復。
- **UAC 提權** — 無縫的管理員提權，用於編輯系統變數。
- **即時廣播** — 透過 `WM_SETTINGCHANGE` 將變更立即廣播至整個系統。

## 100% 離線 · 完全免費

EnvStudio **不連網、不上傳資料、不包含任何遙測或統計埋點。** 您的環境變數設定始終只儲存在自己的電腦上。

所有功能**完全免費**，無廣告，無付費牆。未來可能會增加捐贈入口，但不會對任何功能收費。

詳情請參閱[隱私政策](https://prunelab.net/zh-tw/products/envstudio/privacy)。

---

## 回饋入口

> **注意：** 本倉庫**不包含** EnvStudio 的原始程式碼，僅用於收集使用者回饋和問題追蹤。

| 操作 | 連結 |
|------|------|
| 回饋 Bug | [提交 Bug 報告](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| 功能建議 | [提交新功能建議](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| 檢視全部 Issues | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## 回饋前須知

請先搜尋[已有 Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues)，避免重複提交。

提交 Bug 報告時請包含：
- **EnvStudio 版本**（在「設定 → 關於」中檢視）
- **Windows 版本**（如 Windows 11 23H2）
- **重現步驟**
- **期望行為** vs **實際行為**
- 螢幕截圖（如有）

## 功能建議

我們很樂意聽到你的想法！提交前請注意：
- 檢查是否已有人提出類似建議
- 描述使用場景——這個功能能解決什麼問題？
- 歡迎提供示意圖或參考連結
