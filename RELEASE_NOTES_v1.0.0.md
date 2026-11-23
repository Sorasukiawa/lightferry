# 光渡 Lightferry v1.0.0

拾光改名光渡并发布正式版：通过 Apple 公证，新增多款剪辑工程衔接、视频审片与剪辑代理、更严格的拷卡校验、拷完邮件提醒，并开始收费。

**[下载 DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v1.0.0/Lightferry_1.0.0_aarch64.dmg)** · [安装指南](https://lightferry.app/zh-cn/guides/) · [价格与购买](https://lightferry.app/zh-cn/pricing/) · [授权管理](https://lightferry.app/zh-cn/account/) · [全部版本](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### 新增

- 拾光改名「光渡 Lightferry」：新图标会跟随 macOS 的浅色与深色外观，官网迁到 lightferry.app。
- 剪辑工程衔接：新建项目可选 Final Cut Pro、达芬奇（DaVinci Resolve）、Premiere Pro、剪映或 CapCut，拷卡校验通过后自动送入或生成工程。
- 视频审片与剪辑代理：把视频转成 H.264 审片小样或 ProRes 剪辑代理，支持在 Final Cut Pro、达芬奇、剪映、CapCut 及 Premiere（兼容 PCM 代理）里回链原片。
- 官方 LUT 审片支持：Sony、Canon、Panasonic、Nikon、Fujifilm 与 ARRI 的 Log 素材可以保留 Log 出代理；在审片页可直接按厂商官方直链下载并核对 SHA-256（或手动导入官方 LUT），转成 Rec.709 审片小样。
- 更严格的拷卡校验：可选快速校验、绕缓存完整回读或边拷边验；完成页直接给出「可以格式化／先别格式化」的明确结论。
- 校验失败的文件会被隔离，支持重新校验、外接盘掉线后增量补拷缺失文件，并导出离线 HTML／PDF 报告与 ASC MHL 清单。
- 拷 RAW 卡时保持卡上原有的目录结构与配套文件。
- 拷完邮件提醒与网页授权管理：可在设置里验证通知邮箱，任务结束后自动发送六语邮件告知卡能不能格式化（支持多任务汇总与断网补发）；可在官网 `/zh-cn/account/` 管理与找回授权。
- 项目管理与目录预设永久免费；拷卡与拷贝、归档、转码每类任务各可免费试用 3 次（不限天数）。永久版（2 台 Mac，最多可增购名额至 4 台）在官网购买，30 天短期卡与增购名额在 App 内购买，激活与换机在 App 内完成；永久版付款满 14 天复验后支持长期离线使用。
- 设置里可以打开「接收 Beta 版更新」，并可查看开源组件声明。
- 自动更新优先从官网下载，连不上 GitHub 时也能更新。

### 改进

- 安装包已通过 Apple Developer ID 签名与公证，首次打开不再提示「无法验证开发者」。
- 界面全面换成新版（侧栏入口简化为「拷贝」「转码」「预设」），打开项目、切换页签和展开面板更顺，原生菜单支持六语。
- 打开项目详情更快，不再等磁盘信息查询。
- 拷贝时保留文件的修改时间和用户属性，并逐项核对。
- 开始拷贝前发现读不了的来源文件时，报错会写明是哪个文件。
- 一次拷贝大量小文件时更稳，每个文件仍会确认写进磁盘才算完成。
- 更新说明按界面语言显示（从下一次更新开始生效）。

### 修复

- 修复任务中心切换进行中与已完成页签时内容错乱的问题。
- 修复补拷缺失文件后完成数量不对的问题。
- 修复取消拷卡后仍在等待设备信息查询的问题。
- 修复切换主题与语言时偶尔报错的问题。
- 修复项目详情里插卡提示布局错位的问题。
- 修复部分拷贝错误与复核提示在繁中、英文与日文下未翻译的问题。

### 升级须知

- 从拾光 0.2.x 升级后改为收费模式：每类任务先有 3 次免费试用（历史任务不扣次），用完后需要购买并激活。拾光 0.2.2 不会到期，不升级可以继续免费使用旧版。
- 项目、分组、设置、自定义预设、未保存草稿、卡槽记忆与中断拷贝任务会自动迁移到光渡，旧的数据目录（`com.shiguang.desktop`）原样保留不删。
- 升级后「应用程序」里的 App 外层包名仍叫「拾光」，内部身份已切为光渡。可以直接在 Finder 里改名为「光渡」，不影响后续应用内自动更新。
- 因为签名与身份变了，光渡第一次访问外接盘和网络盘时，macOS 会再询问一次，请选择「允许」。
- **关于回退 0.2.2**：旧数据目录未做破坏性改动，回装 0.2.2 仍可读取升级前的旧资料库，但升级到 1.0 后新增或修改的内容不会反向同步回 0.2.2；若在 0.2.2 写入新改动后再换回 1.0，光渡会弹出分叉提示且不会静默覆盖两边数据。

### 已知问题

- H.264 审片小样是有损压缩，小尺寸代理和高帧率审片的画质略软。
- 部分 Log 曲线、HDR 和 RAW 解码暂不支持转码（RAW 整卡目录拷贝与校验不受影响）。
- 一次拷贝上万个极小文件到 ExFAT 盘或机械硬盘时仍然较慢：每个文件都会确认写进磁盘，优先保证落盘可靠性。

---

Shiguang is now Lightferry, and this is the first full release: signed and notarized by Apple, with direct NLE project handoff, video review copies and editing proxies, stricter card verification, completion email alerts, and paid licensing.

**[Download DMG · Apple Silicon Mac](https://github.com/Sorasukiawa/lightferry/releases/download/v1.0.0/Lightferry_1.0.0_aarch64.dmg)** · [Install guide](https://lightferry.app/guides/) · [Pricing](https://lightferry.app/pricing/) · [License portal](https://lightferry.app/account/) · [All versions](https://github.com/Sorasukiawa/lightferry/blob/main/VERSIONS.md)

### New

- Shiguang is now Lightferry, with a new icon that follows macOS Light and Dark appearance and a new website at lightferry.app.
- Direct NLE handoff: choose Final Cut Pro, DaVinci Resolve, Premiere Pro, CapCut, or Jianying when creating a project, and automatically send or generate project files after verified offload.
- Video review copies and editing proxies: convert clips to H.264 review copies or ProRes proxies with original-media relinking across Final Cut Pro, DaVinci Resolve, CapCut, Jianying, and Premiere Pro (PCM-compatible proxies).
- Official camera LUT support: keep Sony, Canon, Panasonic, Nikon, Fujifilm, and ARRI Log footage in Log for proxies, or download official camera-maker LUTs directly from vendor links with SHA-256 verification (or import manually) to generate Rec. 709 review copies.
- Stricter card verification: choose Fast, Full cache-bypass read-back, or verify-while-copying, and get a plain "Safe to format" or "Do not format yet" verdict on the completion screen.
- Files that fail verification are quarantined; you can re-verify, resume incrementally after an external drive disconnect without rewriting verified files, and export offline HTML/PDF reports plus ASC MHL manifests.
- RAW cards preserve their original folder structure and sidecar files.
- Completion email alerts and web license portal: verify an email in Settings to receive six-language completion emails stating whether a card is safe to format (with multi-task batching and offline retry), and manage or recover licenses at `/account/`.
- Project organization and folder presets are free forever. Card offload and copy, archiving, and transcoding each include 3 free trial tasks with no time limit. Perpetual licenses (2 Macs, expandable up to 4 seats) are sold on the website; 30-day passes and extra seats are available in the app, with activation and device switching built in. Perpetual licenses support long-term offline use once past the 14-day refund window.
- Settings includes a "Receive Beta updates" toggle and open-source component notices.
- Automatic updates download from lightferry.app first, so updates keep working even if GitHub is unreachable.

### Improved

- Signed with Apple Developer ID and notarized, so macOS no longer warns that the developer cannot be verified.
- The new interface is now the only interface (with streamlined sidebar labels: Copy, Transcode, Presets), smoother project opening and panels, and six-language native menus.
- Project details open faster without waiting on disk queries.
- Copies preserve file modification times and user attributes, and verify both.
- If a source file can't be read before copying starts, the error names the specific file.
- Copying large batches of small files is more reliable while still confirming each file on disk before counting it as done.
- Update notes follow the app language, starting with the next update.

### Fixed

- Fixed the Task Center mixing up content when switching between In Progress and Completed.
- Fixed the completed count after recopying missing files.
- Fixed canceling a card offload still waiting on a device-information query.
- Fixed occasional errors when switching theme or language.
- Fixed the card prompt layout in project details.
- Fixed several copy and verification error messages remaining untranslated in Traditional Chinese, English, and Japanese.

### Before you upgrade

- Upgrading from Shiguang 0.2.x switches to paid licensing: each task type starts with 3 free trial tasks (past tasks do not consume trial runs), after which a license is required. Shiguang 0.2.2 never expires and remains free if you choose not to upgrade.
- Projects, groups, settings, custom presets, unsaved drafts, card-slot memory, and interrupted copy tasks migrate automatically to Lightferry, while the old data folder (`com.shiguang.desktop`) is kept untouched.
- After upgrading, the app bundle in Applications keeps the outer name "Shiguang" while running Lightferry internally. You can rename it to "Lightferry" in Finder without affecting future in-app updates.
- Because the bundle identifier and signature changed, macOS asks once more the first time Lightferry accesses external and network drives. Choose Allow.
- **Downgrading to 0.2.2:** Your legacy data folder stays intact, so reinstalling 0.2.2 opens your pre-upgrade library (changes made in 1.0 do not sync back to 0.2.2). If you modify data in 0.2.2 and later return to 1.0, Lightferry shows a divergence warning without silently overwriting either library.

### Known issues

- H.264 review copies are lossy, and small proxies and high-frame-rate review copies can look slightly soft.
- Some Log curves, HDR, and RAW decoding are not yet supported for transcoding (full RAW card offload and verification work as expected).
- Copying tens of thousands of tiny files to ExFAT or spinning hard drives remains slow because each file is confirmed on disk to protect durability.

---

需要 macOS 13 及以上的 Apple Silicon Mac。安装包已通过 Apple Developer ID 签名与公证。项目管理与目录预设永久免费，每类任务可免费试用 3 次，之后需要购买，见[价格](https://lightferry.app/zh-cn/pricing/)。DMG 用于手动安装，`Lightferry_aarch64.app.tar.gz`、`.sig` 和 `latest.json` 供应用内更新使用。拷卡、拷贝或归档进行中不会安装更新。请保留原卡和另一份可靠备份。问题反馈：[Issues](https://github.com/Sorasukiawa/lightferry/issues)；不便公开的问题请发邮件到 [support@lightferry.app](mailto:support@lightferry.app)。

Requires an Apple Silicon Mac with macOS 13 or later. Signed with Apple Developer ID and notarized. Project organization and presets are free forever, and each task type includes 3 free trial tasks; after that a purchase is required, see [Pricing](https://lightferry.app/pricing/). Use the DMG for manual installs; the `.app.tar.gz`, `.sig`, and `latest.json` files serve in-app updates. Updates are not installed while a card offload, copy, or archive is running. Keep the original card and another reliable backup. Report issues on [Issues](https://github.com/Sorasukiawa/lightferry/issues), or email [support@lightferry.app](mailto:support@lightferry.app) for anything private.
