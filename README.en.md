[简体中文](./README.md) · [繁體中文](./README.zh-TW.md) · [English](./README.en.md) · [日本語](./README.ja.md)

<p align="center"><img src="./shiguang-icon.png" width="96" height="96" alt="Lightferry app icon"></p>
<h1 align="center">Lightferry 光渡</h1>
<p align="center"><strong>Bring your footage home with confidence.</strong></p>
<p align="center">Formerly Shiguang 拾光. v0.2.2 still shows the old name after installation; the next release switches to Lightferry.</p>
<p align="center">A Mac media workspace for photographers, DITs, and video production teams. Ingest camera cards, files, and folders; write to multiple destinations; verify each copy; and keep searchable project and task reports.</p>
<p align="center"><a href="https://github.com/Sorasukiawa/shiguang/releases/download/v0.2.2/Shiguang_0.2.2_aarch64.dmg"><strong>Download v0.2.2 · Apple Silicon Mac</strong></a> · <a href="https://getshiguang.pages.dev/guides/">User guides</a> · <a href="https://github.com/Sorasukiawa/shiguang/releases/tag/v0.2.2">What's new</a></p>
<p align="center">Free beta · 简体中文 / 繁體中文 / English / 日本語 · Light and dark themes</p>

![v0.2.1 Mac project workspace with three sample photography projects; dark theme, Chinese interface](./projects-v0.2.1-native-macos.png)

*Native v0.2.1 Apple Silicon Mac window capture. Project names and data come from an isolated demo environment.*

## A clear path for every shoot

| Start with | What Lightferry does | What you can check |
| --- | --- | --- |
| **Camera card ingest** | Finds photo, video, and audio media; organizes by project, shoot date, and camera; reads the source once while writing to a working disk and a second backup | Copy and verification results for each destination, card history, and retry status |
| **File and folder copy** | Takes files from Finder or a picker, preserves folder structure, and writes to one or more destinations | Source list, capacity preflight, transfer results, and retry for incomplete copies |
| **Project media import** | Adds existing media to a chosen project and maps photos, video, audio, and project files into its folders | Import location, project record, and task result |
| **Project archive** | Archives to a local or network destination while retaining the project record; does not automatically delete local media | Archive task, available verification result, and report |

Lightferry **never overwrites existing files**. Multi-destination results are tracked separately. After an interruption or disconnect, it checks destination identity and capacity again before retrying incomplete copies.

### File copy

![v0.2.1 Mac file-copy screen with a sample source, two destinations, and full verification; Chinese interface](./file-copy-v0.2.1-native-macos.png)

*Native v0.2.1 Apple Silicon Mac window capture. Paths and files come from an isolated demo environment.*

### Task reports

Find results by project, date, type, and status; export an offline HTML or multipage PDF report. Missing fields in older records are marked as unknown rather than treated as success.

<img src="./report-v0.2.1-synthetic.png" width="480" alt="v0.2.1 PDF task report with synthetic data showing interrupted and failed tasks; Chinese content">

*v0.2.1 report example; all content is synthetic.*

## Get started

1. Download the **Apple Silicon Mac** DMG above. There is no public Intel Mac or Windows installer. Check your chip in **Apple menu → About This Mac**.
2. Open the DMG and drag Shiguang into Applications (v0.2.2 still uses the old name). If macOS blocks the first launch, verify the app in **System Settings → Privacy & Security** and choose **Open Anyway**. You do not need to disable Gatekeeper.
3. Add a source, project, and destinations. Review capacity and verification before starting. Keep the original card and another reliable backup for important media; format the card only after checking the copies.

This is a **free beta** with an ad-hoc signature, without Apple Developer ID signing or notarization. Download only from [this repository's Releases](https://github.com/Sorasukiawa/shiguang/releases). Active ingest, file-copy, or archive tasks block installation of an update.

## Current release · v0.2.2

- Clearer task-report layouts, pagination, and content.
- Completion notifications open the matching report; clicks and pending reports persist.
- Confirmed reminders are not resent after clearing notifications or restarting; unknown outcomes pause automatic retries.
- Related settings switches correctly respect their disabled state.

[Full release notes](https://github.com/Sorasukiawa/shiguang/releases/tag/v0.2.2) · [All versions](./VERSIONS.md)

<details>
<summary>Verification, storage, and network folders</summary>

- **No verification** only relies on write errors and is unsuitable for important media. **Fast verification** rereads each destination file and compares its XXH64 with the hash computed from the source during copying. **Full verification** independently rereads every source file too. XXH64 detects content differences; it is not a cryptographic signature. Spot-check critical media even after verification passes.
- APFS is recommended for working, second-backup, and archive destinations. ExFAT can be a destination only if it passes Lightferry's safety capability check; otherwise writing is refused before it starts. An ExFAT camera card can be a read-only source. Lightferry does not require formatting existing media.
- Scanning, copying, verification, and project records are local by default; Lightferry does not upload photos or video to its own server. If you choose a NAS or third-party sync folder, the operating system or service handles subsequent network transfer or sync. Check disconnect and sync behavior in your own environment.

</details>

## Help and feedback

[Website](https://getshiguang.pages.dev/) · [Guides](https://getshiguang.pages.dev/guides/) · [Report an issue](https://github.com/Sorasukiawa/shiguang/issues) · Private support: [support@lightferry.app](mailto:support@lightferry.app)

Include the app version, macOS version and chip, source and destination formats, reproduction steps, and complete error text. Redact project names and paths in screenshots. **Do not upload original media or client information.**

This repository hosts installers, documentation, release history, and feedback. **It does not contain the Lightferry app source code or grant an open-source or redistribution license.** GitHub's automatic Source code archives contain only this repository's public materials; they are not app installers.
