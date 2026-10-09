# 光渡 Lightferry v0.2.2

本版改进任务报告、完成通知与通知点击恢复，并修复设置开关的禁用状态。

**[下载 v0.2.2 DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg)** · [安装指南](https://getshiguang.pages.dev/guides/) · [全部版本](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

## 简体中文

- 多个任务同批结束时，完成提示逐一保留，失败提示优先。
- 修复报告结束日最后一秒的筛选遗漏；减少动态效果时，相关提示不再位移，完成对勾立即显示。
- 文件拷贝与素材导入的启动／重试预检使用阻塞线程，减少慢盘 I/O 对异步执行器的占用。

- 任务报告的布局、分页与内容展示更清晰。
- 拷卡、文件拷贝、素材导入和归档完成后，可通过 macOS 通知打开对应报告；通知点击与待打开报告会持久保存。
- 已确认发送的通知，即使从通知中心清除、退出或重启 App，也不会自动重复发送。发送结果不明时暂停自动重发，优先避免重复，因此极少数异常退出场景可能漏掉一次提醒；任务结果仍可在 App 中查看。
- 修复关闭上级选项后，相关设置开关仍能点击的问题。

## 繁體中文

- 多個工作同批完成時保留每一則提示，失敗提示優先。
- 修正報告結束日期最後一秒的篩選遺漏；減少動態效果時提示不再位移，完成勾選立即顯示。
- 檔案複製與素材匯入的啟動／重試預檢使用阻塞執行緒，減少慢速磁碟對非同步執行器的占用。

- 工作報告的版面、分頁與內容更清晰。
- 轉存、檔案複製、素材匯入與封存完成後，可透過 macOS 通知開啟對應報告；通知點擊與待開啟報告會持久保存。
- 已確認傳送的通知，在通知中心清除、結束或重新啟動 App 後不會自動重送。結果不明時暫停自動重送，優先避免重複，因此少數異常退出情況可能漏掉一次提醒；工作結果仍可在 App 中查看。
- 修正關閉上層選項後，相關設定開關仍可點擊的問題。

## English

- Keep every completion notice when several tasks finish in one refresh, with failures first.
- Include the final fractional second in report date filters. Related notices respect reduced motion, and completion checkmarks appear immediately.
- Run file-copy and media-import start/retry preflight on blocking threads, reducing slow-disk I/O on the async executor.

- Clearer task-report layouts, pagination, and content.
- Open the matching report from a macOS completion notification for offloads, file copies, media imports, and archives. Notification clicks and pending reports persist across app restarts.
- Confirmed notifications are not automatically resent after clearing Notification Center or restarting the app. Unknown delivery outcomes pause automatic retries to prioritize avoiding duplicates. Rare crashes may therefore miss a reminder; task results remain available in the app.
- Related settings switches now correctly become disabled when their parent option is turned off.

## 日本語

- 同時に終了した複数の作業の通知をすべて保持し、失敗を優先して表示します。
- レポートの日付絞り込みで最終日の最後の1秒を含めます。視差効果を減らす設定では通知の移動を抑え、完了マークをすぐ表示します。
- コピーと素材追加の開始・再試行の事前確認を専用スレッドで実行し、低速ディスクによる非同期実行器の占有を減らします。

- 作業レポートのレイアウト、改ページ、内容表示を改善しました。
- 取り込み、ファイルコピー、素材追加、アーカイブの完了通知から該当レポートを開けます。通知のクリックと未表示レポートは再起動後も保持されます。
- 送信確認済みの通知は、通知センターから消去したり App を再起動したりしても自動再送されません。結果が不明な場合は重複防止を優先して自動再送を停止するため、まれな異常終了時に通知が一度届かない可能性があります。作業結果は App 内で確認できます。
- 上位の設定を無効にした際、関連するスイッチも正しく操作不可になります。

---

Apple Silicon macOS 免费内测版／免費測試版／free beta／無料ベータ版。采用 ad-hoc 签名，未获 Apple Developer ID 签名或公证；本版不包含开发中的视频编码功能。

DMG 供手动安装；`Lightferry_aarch64.app.tar.gz`、`.sig` 与 `latest.json` 供应用内更新使用。GitHub 的 Source code 归档仅含公开资料，不包含 App 源码。正在执行的传输任务会阻止安装更新。重要素材请保留原卡和另一份可靠备份。
