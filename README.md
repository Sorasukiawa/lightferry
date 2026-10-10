[简体中文](./README.md) · [繁體中文](./README.zh-TW.md) · [English](./README.en.md) · [日本語](./README.ja.md)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./brand/lockup-icon-white.svg">
    <img src="./brand/lockup-icon-ink.svg" width="240" alt="光渡 Lightferry">
  </picture>
</p>

<h3 align="center">让每一束光，安然抵达。</h3>

<p align="center">面向摄影师、DIT 与影像制作团队的 Mac 素材工作台。<br>读一次相机卡，同时写入工作盘与备份盘；逐份校验，按项目归位，留下可查的报告。</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/latest"><img alt="最新版本" src="https://img.shields.io/github/v/release/Sorasukiawa/lightferry?style=flat-square&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC&labelColor=0B1A24&color=E2AC4A"></a>
  <img alt="macOS 13 及以上 · Apple Silicon" src="https://img.shields.io/badge/macOS%2013%2B-Apple%20Silicon-143240?style=flat-square&logo=apple&logoColor=white&labelColor=0B1A24">
  <img alt="免费内测 · 四种语言" src="https://img.shields.io/badge/%E5%85%8D%E8%B4%B9%E5%86%85%E6%B5%8B-%E5%9B%9B%E7%A7%8D%E8%AF%AD%E8%A8%80-143240?style=flat-square&labelColor=0B1A24">
</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg"><strong>下载 v0.2.2 · Apple Silicon Mac</strong></a>
  &nbsp;·&nbsp; <a href="https://getshiguang.pages.dev/guides/">使用指南</a>
  &nbsp;·&nbsp; <a href="https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2">本次更新</a>
  &nbsp;·&nbsp; <a href="./VERSIONS.md">全部版本</a>
</p>

> [!IMPORTANT]
> 当前为免费内测版，采用 ad-hoc 签名，尚无 Apple Developer ID 签名或 Apple 公证。请只从[本仓库 Releases](https://github.com/Sorasukiawa/lightferry/releases) 下载，首次打开的步骤见[开始使用](#开始使用)。

<img src="./screenshot-ingest-zh-CN.webp" alt="光渡拷卡页：识别到存储卡后选择项目与机位，同时写入两块硬盘，并选择完整校验">

<p align="center"><sub>Mac 上的实际窗口截图：插卡后选好项目与机位，同时写入两块硬盘并完整校验。示例项目与文件夹为演示用。</sub></p>

## 拷贝 · 校验 · 整理

<table>
  <tr>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/offload-dawn.svg"><img src="./brand/icons/offload-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>相机卡拷卡</strong><br>
      <sub>插卡自动识别照片、视频与音频，按项目、拍摄日与机位归位。读取一次来源，同时写入工作盘与第二备份盘。</sub>
    </td>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/copy-dawn.svg"><img src="./brand/icons/copy-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>文件与文件夹拷贝</strong><br>
      <sub>从 Finder 拖入或选择来源，保留目录层级，原样写入一个或多个目的地；开始前预检空间。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/organize-dawn.svg"><img src="./brand/icons/organize-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>项目素材导入</strong><br>
      <sub>把已有素材加入指定项目，按照片、视频、音频、工程文件等类别放进项目目录。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/archive-dawn.svg"><img src="./brand/icons/archive-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>项目归档</strong><br>
      <sub>把项目归档到本地或网络目标，归档前强制完整校验；保留原项目记录，不会自动删除本地素材。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/verify-dawn.svg"><img src="./brand/icons/verify-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>三档校验</strong><br>
      <sub>不校验、快速校验、完整校验按素材重要程度选择；每个目的地单独给出校验结果。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/recovery-dawn.svg"><img src="./brand/icons/recovery-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>中断恢复与补拷</strong><br>
      <sub>中断、目标掉线或盘满后，先重新确认目标身份和空间，再只补未完成的副本，不重写已完成的文件。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/report-dawn.svg"><img src="./brand/icons/report-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>任务报告</strong><br>
      <sub>按项目、日期、类型与状态查找任务结果，导出离线 HTML 或多页 PDF；完成通知可直接打开对应报告。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/presets-dawn.svg"><img src="./brand/icons/presets-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>文件夹预设</strong><br>
      <sub>内置视频、照片与混合项目的目录结构，可复制后自定义；新建项目时自动生成整套文件夹。</sub>
    </td>
  </tr>
</table>

## 三条底线

- **不覆盖已有文件。** 遇到同名内容由你决定跳过或两份都保留，光渡不会静默替换。
- **每一份副本都有自己的结果。** 多目标任务分别记录拷贝与校验状态；中断或目标掉线后，先重新确认目标身份和空间，再补齐未完成的副本。
- **一切在本机完成。** 素材扫描、拷贝、校验和项目记录默认在本机完成，不会上传到光渡服务器。

## 为什么不直接用 Finder 拖？

| | Finder 拖拽 | 光渡 |
| --- | --- | --- |
| 写入两块盘 | 分两次拖，卡要读两遍 | 读一次卡，同时写入 |
| 拷完核对 | 不核对内容 | 快速或完整校验，逐份给出结果 |
| 拔盘或中断 | 从头再来，或自己比对 | 只补未完成的文件 |
| 同名文件 | 可能提示替换 | 绝不覆盖已有文件 |
| 文件夹 | 手动新建 | 按项目、拍摄日与机位自动归位 |
| 留档 | 没有记录 | 任务报告，可导出 HTML 或 PDF |

## 从插卡到归档

1. **收取**：插入相机卡，或拖入文件与文件夹；选择项目与机位，按拍摄日过滤。
2. **落盘**：读取一次来源，同时写入工作盘与备份盘；开始前先预检空间与目标身份。
3. **校验**：快速校验回读每份副本比对 XXH64；完整校验再独立重读来源。
4. **留档**：任务结果可查找、导出；项目可归档到本地或网络目标，并保留记录。

## 看看界面

### 项目工作台

<img src="./screenshot-projects-zh-CN.webp" alt="光渡项目页：三个示例项目的卡片，显示类型、拍摄日、素材量与文件数">

每个项目一张卡片，显示类型、拍摄日、素材量与文件数；拷卡完成后还会标出是否双备份、是否通过校验。可以按进行中、已完成、已归档与回收站筛选，也可以分组。

### 文件拷贝

<img src="./screenshot-copy-zh-CN.webp" alt="光渡文件拷贝页：一个示例来源文件夹、两个位于不同硬盘的目的地，以及选中的完整校验">

文件与文件夹原样拷到一个或多个位置，保留目录层级；开始前显示每个目的地的剩余空间与所需空间，拷完逐份校验。

### 任务报告

拷卡、文件拷贝、素材导入与归档完成后，都能在任务报告里按项目、日期、类型与状态查找，并导出离线 HTML 或多页 PDF。旧记录缺失的字段会标为「未记录」，不会推定成功。

<p><sub>以上均为 Mac 上的实际窗口截图；项目、文件与路径为演示用。</sub></p>

## 校验方式

- **不校验**：只依据写入过程是否报错。适合临时文件，不适合重要素材。
- **快速校验**：重读每份目标文件，计算 XXH64 与写入时的来源哈希比对。适合日常拷卡与文件拷贝。
- **完整校验**：在快速校验之上，再独立重读全部来源文件。适合重要素材、双备份与归档。

XXH64 用于检测内容差异，不是加密签名；通过后仍应人工抽查关键素材。

## 开始使用

1. 在上方下载 **Apple Silicon Mac** 版 DMG；Intel Mac 与 Windows 暂无公开安装包。可在 ** → 关于本机** 查看芯片。
2. 打开 DMG，把光渡拖进「应用程序」。首次启动若被 macOS 拦截，前往 **系统设置 → 隐私与安全性**，核对应用后选择「仍要打开」。无需关闭 Gatekeeper。
3. 在设置里选好工作盘与备份盘，新建项目，插卡即可开始。重要素材请保留原卡及另一份可靠备份，确认副本后再格式化卡片。

- **芯片**：Apple Silicon（M 系列）
- **系统**：macOS 13 及以上
- **存储**：工作盘、备份盘与归档目标推荐 APFS；通过安全能力检查的 ExFAT 可作目标，ExFAT 相机卡可作只读来源

正在运行的拷卡、文件拷贝或归档任务会阻止更新安装。

## 常见问题

<details>
<summary><strong>Mac 提示无法打开怎么办？</strong></summary>

当前公开测试版尚未通过 Apple 公证。确认文件来自本仓库 Releases 后，按上方「开始使用」第 2 步在「隐私与安全性」里选择「仍要打开」。[查看安装帮助](https://getshiguang.pages.dev/download/#download-help)

</details>

<details>
<summary><strong>中途拔盘或任务失败，需要全部重拷吗？</strong></summary>

不需要。先保留原卡、现有副本和任务记录，重新连接原设备，再从任务恢复入口检查状态。恢复会检查已完成文件，并补齐未完成部分；不要先删除已有副本。

</details>

<details>
<summary><strong>校验没有通过，能格式化原卡吗？</strong></summary>

先不要格式化。检查每一个目标盘的结果，保留原卡和正确副本，按失败记录排查并重试。进度到 100% 不等于所有副本都已通过校验。[了解完成后的检查](https://getshiguang.pages.dev/guides/first-ingest/)

</details>

<details>
<summary><strong>可以直接拷到 NAS 吗？</strong></summary>

拷卡需要先写入本地或外接盘，再从项目详情归档到 NAS。[查看 NAS 归档指南](https://getshiguang.pages.dev/guides/connect-nas/)

</details>

<details>
<summary><strong>本地归档完成，就是网盘上传成功了吗？</strong></summary>

不是。光渡确认的是本地复制和校验，网盘上传是否完成，需要在网盘客户端和云端另外确认。[查看网盘同步指南](https://getshiguang.pages.dev/guides/baidu-sync/)

</details>

<details>
<summary><strong>支持 Intel Mac、Windows 吗？现在收费吗？</strong></summary>

当前公开版仅支持 Apple 芯片 Mac，免费使用，无需申请或付款。正式收费前会另行公布价格与授权规则。

</details>

## 当前版本 · v0.2.2

- 改进任务报告的布局、分页与内容展示。
- 完成通知可打开对应报告，点击与待打开报告持久保存。
- 清除通知、退出或重启后不会重复发送已确认的提醒；结果不明时暂停自动重发。
- 修复设置子开关的禁用状态。

[阅读完整发布说明](https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2) · [浏览所有版本](./VERSIONS.md)

<details>
<summary>存储盘与网络目录</summary>

- 工作盘、第二备份盘和归档目标推荐 APFS。ExFAT 可作为目标盘，但必须先通过光渡的安全能力检查；无法证明安全时会在写入前拒绝。ExFAT 相机卡可作为只读来源。光渡不会要求格式化已有介质。
- 若选择 NAS 或第三方同步文件夹作为归档目标，光渡只确认本地复制与校验；后续网络传输或同步由对应系统与服务处理，网络盘断连和同步服务的行为仍需按实际环境核对。

</details>

## 帮助与反馈

- **[使用指南](https://getshiguang.pages.dev/guides/)**：安装、拷卡、恢复中断任务与归档的图文步骤。
- **[提交问题或建议](https://github.com/Sorasukiawa/lightferry/issues/new/choose)**：按表单填写版本、macOS 与芯片型号、来源和目标格式、复现步骤及错误文字。
- **[提问与交流](https://github.com/Sorasukiawa/lightferry/discussions)**：使用问题、工作流与想法。
- **不便公开的问题**：发邮件到 [support@lightferry.app](mailto:support@lightferry.app)；安全问题请看 [SECURITY.md](./SECURITY.md)。

截图请遮挡项目名和路径，**不要上传原始素材或客户资料**。

## 关于本仓库

> [!NOTE]
> 本仓库用于发布安装包、说明、版本记录与反馈。**仓库不包含光渡 App 源代码，未提供开源许可证或再分发授权**，详见 [LICENSE.md](./LICENSE.md)。GitHub 自动生成的 Source code 压缩包只是本仓库公开资料，不能安装为光渡。
