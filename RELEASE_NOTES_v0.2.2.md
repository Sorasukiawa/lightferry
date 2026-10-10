# 光渡 Lightferry v0.2.2

完成通知可以直接打开对应的任务报告，并修复通知重复发送和设置开关的问题。

**[下载 DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg)** · [安装指南](https://getshiguang.pages.dev/guides/) · [全部版本](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### 新增

- 拷卡、文件拷贝、素材导入和归档完成后，点 macOS 通知即可打开对应报告；退出或重启 App 后照样能打开。

### 改进

- 任务报告的版式和分页更清楚。
- 多个任务同时结束时，每条完成提示都会保留，失败的排在前面。
- 开启「减少动态效果」后，提示不再滑动，完成对勾直接显示。
- 在慢速硬盘上开始或重试文件拷贝、素材导入时，对 App 其他操作的影响更小。

### 修复

- 修复清除通知中心或重启 App 后，已发送的完成通知再次发送的问题。
- 修复按日期筛选报告时，漏掉结束日最后一秒内任务的问题。
- 修复关闭上级选项后，下级设置开关仍能点击的问题。

### 已知问题

- 为避免重复提醒，无法确认通知是否已发出时不会自动重发，所以 App 极少数情况下异常退出后可能少一次提醒。任务结果仍可在 App 里查看。

---

Completion notifications now open the matching task report. This release also fixes duplicate notifications and settings switches.

**[Download DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg)** · [Install guide](https://getshiguang.pages.dev/guides/) · [All versions](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### New

- Click a macOS completion notification for a card offload, file copy, media import, or archive to open its report, even after quitting or restarting the app.

### Improved

- Clearer task-report layout and pagination.
- When several tasks finish at once, every completion notice is kept, with failures first.
- With Reduce Motion on, notices no longer slide and the completion checkmark appears immediately.
- Starting or retrying a file copy or media import on a slow drive has less impact on the rest of the app.

### Fixed

- Fixed completion notifications being sent again after clearing Notification Center or restarting the app.
- Fixed report date filters missing tasks in the final second of the end date.
- Fixed settings switches staying clickable after their parent option was turned off.

### Known issues

- To avoid duplicates, a notification is not resent automatically when its delivery can't be confirmed, so in rare cases an unexpected quit can cause one reminder to be missed. Task results are always available in the app.

---

需要 macOS 13 及以上的 Apple Silicon Mac。安装包为 ad-hoc 签名，尚未获得 Apple Developer ID 签名与公证；开售前可免费使用；本版不含视频编码功能。DMG 用于手动安装，`Lightferry_aarch64.app.tar.gz`、`.sig` 和 `latest.json` 供应用内更新使用。请保留原卡和另一份可靠备份。问题反馈：[Issues](https://github.com/Sorasukiawa/lightferry/issues)。

Requires an Apple Silicon Mac with macOS 13 or later. Ad-hoc signed, not yet signed with Apple Developer ID or notarized; free to use until paid sales open. This version does not include video encoding. Use the DMG for manual installs; the `.app.tar.gz`, `.sig`, and `latest.json` files serve in-app updates. Keep the original card and another reliable backup. Report issues on [Issues](https://github.com/Sorasukiawa/lightferry/issues).
