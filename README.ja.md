[简体中文](./README.md) · [繁體中文](./README.zh-TW.md) · [English](./README.en.md) · [日本語](./README.ja.md)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./brand/lockup-icon-white.svg">
    <img src="./brand/lockup-icon-ink.svg" width="240" alt="光渡 Lightferry">
  </picture>
</p>

<h3 align="center">撮りためた光を、次の場所へ。</h3>

<p align="center">写真家、DIT、映像制作チームのための Mac 用素材ワークスペース。<br>カメラカードを一度読み、作業用ディスクとバックアップへ同時に書き込み、コピーを一つずつ検証し、プロジェクトごとに整理して、後から確認できるレポートを残します。</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/latest"><img alt="最新版" src="https://img.shields.io/github/v/release/Sorasukiawa/lightferry?style=flat-square&label=%E6%9C%80%E6%96%B0%E7%89%88&labelColor=0B1A24&color=E2AC4A"></a>
  <img alt="macOS 13 以降 · Apple Silicon" src="https://img.shields.io/badge/macOS%2013%2B-Apple%20Silicon-143240?style=flat-square&logo=apple&logoColor=white&labelColor=0B1A24">
  <img alt="無料ベータ · 4 言語" src="https://img.shields.io/badge/%E7%84%A1%E6%96%99%E3%83%99%E3%83%BC%E3%82%BF-4%20%E8%A8%80%E8%AA%9E-143240?style=flat-square&labelColor=0B1A24">
</p>

<p align="center">
  <a href="https://github.com/Sorasukiawa/lightferry/releases/download/v0.2.2/Lightferry_0.2.2_aarch64.dmg"><strong>v0.2.2 をダウンロード · Apple Silicon Mac</strong></a>
  &nbsp;·&nbsp; <a href="https://getshiguang.pages.dev/guides/">使い方</a>
  &nbsp;·&nbsp; <a href="https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2">更新内容</a>
  &nbsp;·&nbsp; <a href="./VERSIONS.md">すべてのバージョン</a>
</p>

> [!IMPORTANT]
> 現在は無料ベータ版です。ad-hoc 署名を使用しており、Apple Developer ID 署名と公証はありません。[このリポジトリの Releases](https://github.com/Sorasukiawa/lightferry/releases) からのみ入手してください。初回起動の手順は[使い始める](#使い始める)をご覧ください。

<img src="./screenshot-ingest-ja.webp" alt="光渡の取り込み画面：カードを検出し、プロジェクトとカメラを選択、2 台のドライブへ同時に書き込み、完全検証を選択">

<p align="center"><sub>Mac 上の実際のウィンドウキャプチャ：カードを挿してプロジェクトとカメラを選び、2 台のドライブへ書き込んで完全に検証します。サンプルのプロジェクトとフォルダーはデモ用です。</sub></p>

## コピー・検証・整理

<table>
  <tr>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/offload-dawn.svg"><img src="./brand/icons/offload-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>カード取り込み</strong><br>
      <sub>カードを挿すと写真・動画・音声を検出し、プロジェクト、撮影日、カメラごとに整理。元カードを一度読み、作業用と二つ目のバックアップ先へ同時に書き込みます。</sub>
    </td>
    <td valign="top" width="50%">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/copy-dawn.svg"><img src="./brand/icons/copy-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>ファイル／フォルダーのコピー</strong><br>
      <sub>Finder からドラッグ、または選択。階層を保ったまま一つ以上の保存先へそのままコピーし、開始前に空き容量を確認します。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/organize-dawn.svg"><img src="./brand/icons/organize-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>プロジェクトへの素材追加</strong><br>
      <sub>既存の素材を指定プロジェクトへ追加し、写真・動画・音声・制作ファイルなどをプロジェクトのフォルダーへ振り分けます。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/archive-dawn.svg"><img src="./brand/icons/archive-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>プロジェクトのアーカイブ</strong><br>
      <sub>ローカルまたはネットワーク先へアーカイブ。完全検証を必ず実行し、プロジェクト記録を保持したまま、ローカル素材を自動削除しません。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/verify-dawn.svg"><img src="./brand/icons/verify-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>3 段階の検証</strong><br>
      <sub>なし・高速・完全を素材の重要度で選択。保存先ごとに検証結果を示します。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/recovery-dawn.svg"><img src="./brand/icons/recovery-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>中断後の復旧と再試行</strong><br>
      <sub>中断、保存先の切断、空き容量不足の後は、保存先の識別情報と空き容量を再確認し、未完了のコピーだけを再試行します。</sub>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/report-dawn.svg"><img src="./brand/icons/report-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>作業レポート</strong><br>
      <sub>プロジェクト、日付、種類、状態で結果を探し、オフライン HTML または複数ページの PDF に書き出し。完了通知から該当レポートを開けます。</sub>
    </td>
    <td valign="top">
      <picture><source media="(prefers-color-scheme: dark)" srcset="./brand/icons/presets-dawn.svg"><img src="./brand/icons/presets-ink.svg" width="32" height="32" alt=""></picture><br>
      <strong>フォルダープリセット</strong><br>
      <sub>映像・写真・ハイブリッド用の内蔵構成を複製してカスタマイズ。新規プロジェクトにはフォルダー一式が自動で作られます。</sub>
    </td>
  </tr>
</table>

## 三つの約束

- **既存ファイルを上書きしません。** 同名のものがあればスキップか両方保持を選べます。黙って置き換えることはありません。
- **コピーごとに結果を残します。** 複数の保存先は別々にコピーと検証の状態を記録。中断や切断の後は保存先の識別情報と空き容量を再確認してから、未完了分だけを再試行します。
- **すべて Mac の中で完結します。** 素材の走査・コピー・検証とプロジェクト記録は既定でローカル処理され、光渡のサーバーへ写真や動画をアップロードしません。

## Finder でドラッグするのと何が違う？

| | Finder でドラッグ | 光渡 |
| --- | --- | --- |
| 2 台への書き込み | 2 回ドラッグ、カードも 2 回読む | 一度読んで同時に書き込み |
| コピー後の確認 | 内容は確認しない | 高速または完全検証、コピーごとに結果 |
| 抜けた・中断した | やり直すか手で比較 | 未完了のファイルだけ再試行 |
| 同名ファイル | 置き換えを提案されることも | 既存ファイルは上書きしない |
| フォルダー | 手作業で作成 | プロジェクト・撮影日・カメラで自動整理 |
| 記録 | 残らない | 作業レポート（HTML／PDF） |

## カードからアーカイブまで

1. **取り込み**：カメラカードを挿す、またはファイルやフォルダーをドラッグ。プロジェクトとカメラを選び、撮影日で絞り込みます。
2. **書き込み**：空き容量と保存先の識別情報を確認してから、元データを一度読み、作業用とバックアップへ同時に書き込みます。
3. **検証**：高速検証は各コピーを読み直して XXH64 を比較。完全検証はさらに元データも独立して読み直します。
4. **保管**：結果は検索・書き出しが可能。プロジェクトは記録を保ったままローカルやネットワーク先へアーカイブできます。

## 画面を見る

### プロジェクト

<img src="./screenshot-projects-ja.webp" alt="光渡のプロジェクト画面：3 件のサンプルプロジェクトのカードに種類、撮影日、素材量、ファイル数を表示">

プロジェクトごとに 1 枚のカードで、種類、撮影日、素材量、ファイル数を表示します。取り込み後は二重バックアップと検証済みかどうかも示します。進行中・完了・アーカイブ済み・ゴミ箱で絞り込み、グループ分けもできます。

### ファイルコピー

<img src="./screenshot-copy-ja.webp" alt="光渡のファイルコピー画面：サンプルの元フォルダー 1 件、別々のドライブにある保存先 2 件、完全検証を選択">

ファイルとフォルダーを階層そのままに一つ以上の場所へコピー。開始前に保存先ごとの空き容量と必要容量を表示し、コピー後に一つずつ検証します。

### 作業レポート

取り込み、ファイルコピー、素材追加、アーカイブが終わると、作業レポートでプロジェクト、日付、種類、状態から探し、オフライン HTML または複数ページの PDF に書き出せます。過去の記録にない項目は「未記録」と示し、成功と推定しません。

<p><sub>いずれも Mac 上の実際のウィンドウキャプチャ。プロジェクト、ファイル、パスはデモ用です。</sub></p>

## 検証の種類

- **なし**：書き込み時のエラーだけを確認します。一時的なファイル向けで、大切な素材には不向きです。
- **高速**：各保存先のファイルを読み直し、コピー時に計算した元ファイルの XXH64 と比較します。日常の取り込みとファイルコピー向けです。
- **完全**：高速検証に加え、すべての元ファイルを独立して読み直します。大切な素材、二重バックアップ、アーカイブ向けです。

XXH64 は内容の差を調べるもので、暗号学的な署名ではありません。検証後も重要な素材は目視で確認してください。

## 使い始める

1. 上の **Apple Silicon Mac** 用 DMG をダウンロードしてください。Intel Mac と Windows 向けの公開インストーラーはありません。チップは ** → この Mac について** で確認できます。
2. DMG を開き、光渡を「アプリケーション」へドラッグします。macOS が初回起動を止めた場合は、**システム設定 → プライバシーとセキュリティ** でアプリを確認し、「このまま開く」を選びます。Gatekeeper を無効にする必要はありません。
3. 設定で作業用とバックアップのディスクを選び、プロジェクトを作り、カードを挿せば始められます。大切な素材は元カードと別の信頼できるバックアップを残し、コピー確認後にカードを初期化してください。

- **チップ**：Apple Silicon（M シリーズ）
- **システム**：macOS 13 以降
- **ストレージ**：作業用・バックアップ・アーカイブ先には APFS を推奨。安全機能の確認を通った ExFAT は保存先に使え、ExFAT のカメラカードは読み取り専用の元データとして使えます

カード取り込み、ファイルコピー、アーカイブの実行中は更新をインストールできません。

## よくある質問

<details>
<summary><strong>Mac でアプリを開けない場合は？</strong></summary>

公開ベータ版は Apple の公証を受けていません。このリポジトリの Releases から取得したファイルであることを確認し、「使い始める」の手順 2 に従って「プライバシーとセキュリティ」で「このまま開く」を選んでください。[インストールのヘルプ](https://getshiguang.pages.dev/download/#download-help)

</details>

<details>
<summary><strong>ドライブを抜いたり作業が失敗したら、最初からやり直しですか？</strong></summary>

いいえ。元のカード、既存のコピー、作業履歴を残してください。元の機器を再接続して復旧画面を確認します。完了済みファイルを確認し未完了分をコピーするため、先に既存コピーを削除しないでください。

</details>

<details>
<summary><strong>検証に失敗したカードをフォーマットできますか？</strong></summary>

まだフォーマットしないでください。すべての保存先を確認し、元のカードと正常なコピーを保管して、失敗記録をもとに調べて再試行します。進捗 100% は、すべてのコピーが検証に合格したことを意味しません。[取り込み後の確認](https://getshiguang.pages.dev/guides/first-ingest/)

</details>

<details>
<summary><strong>NAS に直接取り込めますか？</strong></summary>

まずローカルまたは外付けドライブに取り込み、プロジェクト詳細から NAS にアーカイブしてください。[NAS へのアーカイブ](https://getshiguang.pages.dev/guides/connect-nas/)

</details>

<details>
<summary><strong>ローカル保存の完了はクラウドへのアップロード完了ですか？</strong></summary>

いいえ。光渡が確認するのはローカルコピーと検証です。アップロードはクラウド用アプリとクラウド上で別途確認してください。[クラウド同期ガイド](https://getshiguang.pages.dev/guides/baidu-sync/)

</details>

<details>
<summary><strong>Intel や Windows に対応していますか？有料ですか？</strong></summary>

現在の公開版は Apple シリコン Mac 専用で、申請や支払いなしで利用できます。有料化前に価格とライセンス条件をお知らせします。

</details>

## 最新版 · v0.2.2

- 作業レポートのレイアウト、改ページ、内容表示を改善しました。
- 完了通知から該当レポートを開けます。クリックと未表示レポートは保持されます。
- 通知の消去や再起動後も送信確認済みの通知は再送しません。結果が不明な場合は自動再送を停止します。
- 関連する設定スイッチの無効状態を修正しました。

[詳しいリリースノート](https://github.com/Sorasukiawa/lightferry/releases/tag/v0.2.2) · [すべてのバージョン](./VERSIONS.md)

<details>
<summary>保存先とネットワークフォルダー</summary>

- 作業用、第二バックアップ、アーカイブ先には APFS を推奨します。ExFAT を保存先に使う場合は光渡の安全機能の確認が必要で、確認できなければ書き込み前に拒否します。ExFAT のカメラカードは読み取り専用の元データとして使えます。既存メディアの初期化は要求しません。
- NAS や外部同期フォルダーをアーカイブ先に選んだ場合、光渡が確認するのはローカルのコピーと検証だけです。その後の転送・同期は OS または各サービスが担当し、切断や同期の動作は利用環境で確認してください。

</details>

## ヘルプとフィードバック

- **[使い方](https://getshiguang.pages.dev/guides/)**：インストール、取り込み、中断した作業の復旧、アーカイブの手順。
- **[問題の報告・機能の提案](https://github.com/Sorasukiawa/lightferry/issues/new/choose)**：フォームでアプリと macOS のバージョン、チップ、元データと保存先の形式、再現手順、エラー全文を入力します。
- **[質問と交流](https://github.com/Sorasukiawa/lightferry/discussions)**：使い方の質問、ワークフロー、アイデア。
- **非公開のお問い合わせ**：[support@lightferry.app](mailto:support@lightferry.app) へ。セキュリティの問題は [SECURITY.md](./SECURITY.md) をご覧ください。

画像のプロジェクト名やパスは隠し、**元の素材や顧客情報はアップロードしないでください**。

## このリポジトリについて

> [!NOTE]
> このリポジトリはインストーラー、説明、リリース履歴、フィードバックを公開します。**光渡アプリのソースコードは含まず、オープンソースライセンスや再配布の許可もありません**（[LICENSE.md](./LICENSE.md)）。GitHub が自動生成する Source code は、このリポジトリの公開資料をまとめたもので、アプリのインストーラーではありません。
