[简体中文](./README.md) · [繁體中文](./README.zh-TW.md) · [English](./README.en.md) · [日本語](./README.ja.md)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./brand/lockup-icon-white.svg">
    <img src="./brand/lockup-icon-ink.svg" width="240" alt="光渡 Lightferry">
  </picture>
</p>

<h3 align="center">讓每一束光，安然抵達。</h3>

<p align="center">為攝影師、DIT 與影像製作團隊設計的 Mac 素材工作台。<br>讀一次記憶卡，同時寫入工作碟與備份碟；逐份驗證，依專案歸位，留下可查的報告。</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/latest"><img alt="最新版本" src="https://img.shields.io/github/v/release/Sorasukiawa/lightferry?style=flat-square&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC&labelColor=0B1A24&color=E2AC4A"></a>
  <img alt="macOS 13 以上 · Apple Silicon" src="https://img.shields.io/badge/macOS%2013%2B-Apple%20Silicon-143240?style=flat-square&logo=apple&logoColor=white&labelColor=0B1A24">
  <img alt="免費試用 · 永久買斷" src="https://img.shields.io/badge/%E5%85%8D%E8%B2%BB%E8%A9%A6%E7%94%A8-%E6%B0%B8%E4%B9%85%E8%B2%B7%E6%96%B7-143240?style=flat-square&labelColor=0B1A24">
</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg"><strong>下載 v0.2.2 · Apple Silicon Mac</strong></a>
  &nbsp;·&nbsp; <a href="https://getshiguang.pages.dev/guides/">使用指南</a>
  &nbsp;·&nbsp; <a href="https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2">本次更新</a>
  &nbsp;·&nbsp; <a href="./VERSIONS.md">全部版本</a>
</p>

> [!IMPORTANT]
> 安裝包目前採用 ad-hoc 簽名，尚未取得 Apple Developer ID 簽名或 Apple 公證。請只從[本倉庫 Releases](https://github.com/Sorasukiawa/lightferry/releases) 下載，首次開啟的步驟見[開始使用](#開始使用)。

<img src="./screenshot-ingest-zh-TW.webp" alt="光渡拷卡頁：辨識到記憶卡後選擇專案與機位，同時寫入兩顆硬碟，並選擇完整驗證">

<p align="center"><sub>Mac 上的實際視窗截圖：插卡後選好專案與機位，同時寫入兩顆硬碟並完整驗證。示例專案與資料夾為演示用。</sub></p>

## 拷貝 · 驗證 · 整理

<table>
  <tr>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/offload-dawn.svg"><img src="./brand/icons/offload-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>記憶卡拷卡</strong><br>
      <sub>插卡自動辨識照片、影片與音訊，依專案、拍攝日與機位歸位。讀取來源一次，同時寫入工作碟與第二備份碟。</sub>
    </td>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/copy-dawn.svg"><img src="./brand/icons/copy-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>檔案與資料夾拷貝</strong><br>
      <sub>從 Finder 拖入或選擇來源，保留資料夾層級，原樣寫入一個或多個目的地；開始前預檢空間。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/organize-dawn.svg"><img src="./brand/icons/organize-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>專案素材匯入</strong><br>
      <sub>把現有素材加入指定專案，依照片、影片、音訊、工程檔等類別放進專案資料夾。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/archive-dawn.svg"><img src="./brand/icons/archive-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>專案封存</strong><br>
      <sub>把專案封存到本機或網路目的地，封存前強制完整驗證；保留原專案紀錄，不會自動刪除本機素材。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/verify-dawn.svg"><img src="./brand/icons/verify-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>三檔驗證</strong><br>
      <sub>不驗證、快速驗證、完整驗證依素材重要程度選擇；每個目的地分別給出驗證結果。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/recovery-dawn.svg"><img src="./brand/icons/recovery-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>中斷復原與補拷</strong><br>
      <sub>中斷、目的地離線或磁碟寫滿後，先重新確認目的地身分與空間，再只補未完成的副本，不重寫已完成的檔案。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/report-dawn.svg"><img src="./brand/icons/report-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>工作報告</strong><br>
      <sub>依專案、日期、類型與狀態搜尋工作結果，匯出離線 HTML 或多頁 PDF；完成通知可直接開啟對應報告。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/presets-dawn.svg"><img src="./brand/icons/presets-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>資料夾預設</strong><br>
      <sub>內建影片、相片與混合專案的目錄結構，可複製後自訂；新建專案時自動產生整套資料夾。</sub>
    </td>
  </tr>
</table>

## 三條底線

- **不覆蓋現有檔案。** 遇到同名內容由你決定跳過或兩份都保留，光渡不會靜默取代。
- **每一份副本都有自己的結果。** 多目的地工作分別記錄拷貝與驗證狀態；中斷或目的地離線後，先重新確認目的地身分與空間，再補齊未完成的副本。
- **一切在本機完成。** 素材掃描、複製、驗證與專案紀錄預設在本機完成，不會上傳到光渡伺服器。

## 為什麼不直接用 Finder 拖？

| | Finder 拖曳 | 光渡 |
| --- | --- | --- |
| 寫入兩顆硬碟 | 分兩次拖，卡要讀兩遍 | 讀一次卡，同時寫入 |
| 拷完核對 | 不核對內容 | 快速或完整驗證，逐份給出結果 |
| 拔碟或中斷 | 從頭再來，或自己比對 | 只補未完成的檔案 |
| 同名檔案 | 可能提示取代 | 絕不覆蓋現有檔案 |
| 資料夾 | 手動新建 | 依專案、拍攝日與機位自動歸位 |
| 留檔 | 沒有紀錄 | 工作報告，可匯出 HTML 或 PDF |

## 從插卡到封存

1. **收取**：插入記憶卡，或拖入檔案與資料夾；選擇專案與機位，依拍攝日篩選。
2. **落盤**：讀取來源一次，同時寫入工作碟與備份碟；開始前先預檢空間與目的地身分。
3. **驗證**：快速驗證回讀每份副本比對 XXH64；完整驗證再獨立重讀來源。
4. **留檔**：工作結果可搜尋、匯出；專案可封存到本機或網路目的地，並保留紀錄。

## 看看介面

### 專案工作台

<img src="./screenshot-projects-zh-TW.webp" alt="光渡專案頁：三個示例專案的卡片，顯示類型、拍攝日、素材量與檔案數">

每個專案一張卡片，顯示類型、拍攝日、素材量與檔案數；拷卡完成後還會標出是否雙備份、是否通過驗證。可依進行中、已完成、已封存與回收站篩選，也可以分組。

### 檔案拷貝

<img src="./screenshot-copy-zh-TW.webp" alt="光渡檔案拷貝頁：一個示例來源資料夾、兩個位於不同硬碟的目的地，以及選取的完整驗證">

檔案與資料夾原樣拷到一個或多個位置，保留資料夾層級；開始前顯示每個目的地的剩餘空間與所需空間，拷完逐份驗證。

### 工作報告

拷卡、檔案拷貝、素材匯入與封存完成後，都能在工作報告裡依專案、日期、類型與狀態搜尋，並匯出離線 HTML 或多頁 PDF。舊紀錄缺少的欄位會標為「未記錄」，不會推定成功。

<p><sub>以上均為 Mac 上的實際視窗截圖；專案、檔案與路徑為演示用。</sub></p>

## 驗證方式

- **不驗證**：只依據寫入過程是否報錯。適合暫存檔案，不適合重要素材。
- **快速驗證**：重讀每份目的地檔案，以 XXH64 比對寫入時的來源雜湊。適合日常拷卡與檔案拷貝。
- **完整驗證**：在快速驗證之上，再獨立重讀所有來源檔案。適合重要素材、雙備份與封存。

XXH64 是內容差異檢查，不是加密簽名；通過後仍應人工抽查關鍵素材。

## 開始使用

1. 下載上方的 **Apple Silicon Mac** DMG；目前沒有 Intel Mac 或 Windows 公開安裝包。可在 ** → 關於這台 Mac** 查看晶片。
2. 開啟 DMG，把光渡拖進「應用程式」。首次開啟若被 macOS 阻止，前往 **系統設定 → 隱私權與安全性**，核對 App 後選擇「仍要打開」。無需關閉 Gatekeeper。
3. 在設定裡選好工作碟與備份碟，新建專案，插卡即可開始。重要素材請保留原卡和另一份可靠備份，確認副本後才格式化記憶卡。

- **晶片**：Apple Silicon（M 系列）
- **系統**：macOS 13 以上
- **儲存**：工作碟、備份碟與封存目的地建議 APFS；通過安全能力檢查的 ExFAT 可作目的地，ExFAT 記憶卡可作唯讀來源

拷卡、檔案拷貝或封存執行時會阻止安裝更新。

## 價格

光渡採用買斷制，沒有訂閱。以下價格自正式版開售起生效；開售前，目前公開的 v0.2.2 仍可免費使用。

| 方案 | 價格 | 包含 |
| --- | --- | --- |
| 免費版 | $0 | 專案、歷史紀錄、報告與預設始終可用；拷卡與檔案拷貝、封存等每類工作各可免費使用 3 次，不限天數 |
| 永久版 | $59，首發首月 $49 | 2 台 Mac 同時使用，永久使用，包含之後的版本更新與大版本升級 |
| 30 天短期卡 | $5 / 台 | 在 App 內購買，不自動續費 |
| 增購裝置 | $29 / 台 | 為永久版訂單增加一台 Mac |

- 所有付費產品購買後 14 天內可全額退款，不問原因。
- 由 Dodo Payments 以美元收款；可依結帳時的匯率以銀行卡等方式付款。
- 購買時取得的權益，不會因日後的銷售政策調整而收回。

## 常見問題

<details>
<summary><strong>Mac 提示無法開啟怎麼辦？</strong></summary>

目前公開測試版尚未通過 Apple 公證。確認檔案來自本倉庫 Releases 後，依上方「開始使用」第 2 步在「隱私權與安全性」選擇「仍要打開」。[查看安裝協助](https://getshiguang.pages.dev/download/#download-help)

</details>

<details>
<summary><strong>中途拔碟或工作失敗，需要全部重拷嗎？</strong></summary>

不需要。先保留原卡、現有副本與工作紀錄，重新連接原裝置，再由工作恢復入口檢查。恢復會檢查已完成檔案並補齊未完成部分；不要先刪除現有副本。

</details>

<details>
<summary><strong>驗證未通過，可以格式化原卡嗎？</strong></summary>

先不要格式化。檢查每個目標碟的結果，保留原卡與正確副本，依失敗紀錄排查並重試。進度 100% 不代表所有副本都已通過驗證。[瞭解完成後的檢查](https://getshiguang.pages.dev/guides/first-ingest/)

</details>

<details>
<summary><strong>可以直接拷到 NAS 嗎？</strong></summary>

拷卡需先寫入本機或外接磁碟，再從專案詳情封存至 NAS。[查看 NAS 封存指南](https://getshiguang.pages.dev/guides/connect-nas/)

</details>

<details>
<summary><strong>本機封存完成，就是網盤上傳成功嗎？</strong></summary>

不是。光渡確認的是本機拷貝與驗證，請在網盤用戶端與雲端另外確認上傳結果。[查看網盤同步指南](https://getshiguang.pages.dev/guides/baidu-sync/)

</details>

<details>
<summary><strong>支援 Intel Mac、Windows 嗎？收費嗎？</strong></summary>

目前公開版僅支援 Apple 晶片 Mac。光渡即將開始收費，採用買斷制：免費版每類工作可用 3 次，永久版 $59（首發首月 $49），詳見[價格](#價格)。開售前，目前公開的 v0.2.2 仍可免費使用。

</details>

## 目前版本 · v0.2.2

- 改善工作報告的版面、分頁與內容呈現。
- 完成通知可開啟對應報告，點擊與待開啟報告持久保存。
- 清除通知、結束或重新啟動後不會重送已確認的提醒；結果不明時暫停自動重送。
- 修正相關設定開關的停用狀態。

[完整版本說明](https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2) · [所有版本](./VERSIONS.md)

<details>
<summary>儲存裝置與網路資料夾</summary>

- 工作碟、第二備份碟及封存目的地建議使用 APFS。ExFAT 可作為目的地，但必須先通過光渡的安全能力檢查；無法確認安全時會在寫入前拒絕。ExFAT 記憶卡可作為唯讀來源。光渡不要求格式化現有媒體。
- 若選擇 NAS 或第三方同步資料夾作為封存目的地，光渡只確認本機複製與驗證；後續網路傳輸或同步由相應系統與服務處理，斷線與同步行為應依實際環境確認。

</details>

## 幫助與回饋

- **[使用指南](https://getshiguang.pages.dev/guides/)**：安裝、拷卡、恢復中斷工作與封存的圖文步驟。
- **[回報問題或建議](https://github.com/Sorasukiawa/lightferry/issues/new/choose)**：依表單填寫版本、macOS 與晶片型號、來源及目的地格式、重現步驟和錯誤文字。
- **[提問與交流](https://github.com/Sorasukiawa/lightferry/discussions)**：使用問題、工作流程與想法。
- **不便公開的問題**：寄信到 [support@lightferry.app](mailto:support@lightferry.app)；安全問題請看 [SECURITY.md](./SECURITY.md)。

截圖請遮蔽專案名稱與路徑，**不要上傳原始素材或客戶資料**。

## 關於本倉庫

> [!NOTE]
> 本倉庫用於發佈安裝包、說明、版本紀錄與回饋。**不包含光渡 App 原始碼，沒有提供開源授權或再散佈權利**，詳見 [LICENSE.md](./LICENSE.md)。GitHub 自動產生的 Source code 壓縮檔只是本倉庫的公開資料，不能用來安裝光渡。
