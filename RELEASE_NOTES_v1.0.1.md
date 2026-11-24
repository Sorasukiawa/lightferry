# 光渡 Lightferry v1.0.1

修复版：设置和预设不再因文件损坏而丢失，插回拷过的卡可以直接补做复核，外语界面和导出报告不再夹着简体中文。

**[下载 DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v1.0.1/Lightferry_1.0.1_aarch64.dmg)** · [安装指南](https://lightferry.app/zh-cn/guides/) · [价格与购买](https://lightferry.app/zh-cn/pricing/) · [授权管理](https://lightferry.app/zh-cn/account/) · [全部版本](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### 改进

- 打开光渡和拷大量小文件更快；插回拷过的存储卡时，「能不能格式化」和补做存储卡复核排在拷卡页最前面。

### 修复

- 修复设置文件损坏后工作盘、备份盘和邮件提醒设置被清空的问题：现在会换回上次的设置并提示；预设文件损坏时也不再打不开光渡。
- 修复报告和资料库备份存不到 ExFAT 格式外接盘的问题。
- 修复某个外接盘读不动时，插拔存储卡没有反应、重读存储卡一直转圈的问题。
- 修复繁体中文、英文、日文、韩文和西班牙文界面里，部分失败原因、提示和导出报告仍显示简体中文的问题。

---

Bug-fix release: settings and presets survive a damaged file, a card you have already offloaded can be re-read as soon as you reinsert it, and localized screens and exported reports no longer show Simplified Chinese.

**[Download DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v1.0.1/Lightferry_1.0.1_aarch64.dmg)** · [Install guide](https://lightferry.app/guides/?lang=en) · [Pricing](https://lightferry.app/pricing/?lang=en) · [License portal](https://lightferry.app/account/?lang=en) · [All versions](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### Improved

- Lightferry opens faster and copies large numbers of small files faster. When you reinsert a card you have already offloaded, whether it is safe to format and Re-Read Card now appear at the top of the Ingest page.

### Fixed

- Fixed work drive, backup drive, and email alert settings being cleared after the settings file was damaged. Lightferry now restores your last settings and tells you; a damaged presets file no longer stops Lightferry from opening.
- Fixed reports and library backups failing to save to ExFAT-formatted external drives.
- Fixed card insertion not being detected and Re-Read Card spinning forever while another external drive was unresponsive.
- Fixed some failure reasons, notices, and exported reports showing Simplified Chinese in the Traditional Chinese, English, Japanese, Korean, and Spanish interfaces.

---

需要 macOS 13 及以上的 Apple Silicon Mac。安装包已通过 Apple Developer ID 签名与公证。项目管理与目录预设永久免费，每类任务可免费试用 3 次，之后需要购买，见[价格](https://lightferry.app/zh-cn/pricing/)。DMG 用于手动安装，`Lightferry_aarch64.app.tar.gz`、`.sig` 和 `latest.json` 供应用内更新使用。拷卡、拷贝或归档进行中不会安装更新。请保留原卡和另一份可靠备份。问题反馈：[Issues](https://github.com/Sorasukiawa/lightferry/issues)；不便公开的问题请发邮件到 [support@lightferry.app](mailto:support@lightferry.app)。

Requires an Apple Silicon Mac with macOS 13 or later. Signed with Apple Developer ID and notarized. Project organization and presets are free forever, and each task type includes 3 free trial tasks; after that a purchase is required, see [Pricing](https://lightferry.app/pricing/?lang=en). Use the DMG for manual installs; the `.app.tar.gz`, `.sig`, and `latest.json` files serve in-app updates. Updates are not installed while a card offload, copy, or archive is running. Keep the original card and another reliable backup. Report issues on [Issues](https://github.com/Sorasukiawa/lightferry/issues), or email [support@lightferry.app](mailto:support@lightferry.app) for anything private.
