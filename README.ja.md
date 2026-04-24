# EnvStudio フィードバック

<p align="right">
  <a href="README.md">English (US)</a>
  |
  <a href="README.zh-Hans.md">简体中文</a>
  |
  <a href="README.zh-Hant.md">繁體中文</a>
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

## EnvStudio について

**EnvStudio** は、WinUI 3 で構築されたモダンな Windows 環境変数マネージャーです。20 年間ほとんど変わらなかった「システムのプロパティ → 環境変数」ダイアログを、ネイティブな Windows 11 体験に置き換えます。

<p align="center">
  <img src="https://prunelab.net/products/envstudio/covers/ja/cover1.png" width="48%" />
  <img src="https://prunelab.net/products/envstudio/covers/ja/cover2.png" width="48%" />
</p>

<p align="center">
  <a href="https://apps.microsoft.com/detail/9nl5scxw3320" target="_blank">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Download from Microsoft Store"/>
  </a>
</p>

## 主な機能

- **直感的なビジュアルエディター** — モダンな WinUI 3 インターフェースで、環境変数の追加、編集、削除、並べ替えを簡単に。
- **PATH リスト管理** — ドラッグ＆ドロップによる並べ替え、重複検出、リンク切れ検出。
- **EXE 競合検出** — PATH 内の全ディレクトリの実行可能ファイルをスキャンし、リスト前方のエントリによって上書きされているものを表示。ワンクリックで競合エントリにジャンプ。
- **スコープ衝突検出** — ユーザー変数が同名のシステム変数を隠している場合、取り消し線と警告アイコンで実際に有効な値を常に把握。
- **非破壊トグル** — 変数を削除せずに無効化。レジストリ値を静かにリネームして元データを保持。ワンクリックでいつでも再有効化。
- **削除安全性チェック** — 変数の削除前に他の変数の `%VARNAME%` 参照をスキャンし、潜在的な破損を警告。
- **変数展開プレビュー** — `%VAR%` 参照を含む値にホバーすると、ツールチップで完全に解決されたパスを表示。
- **外部変更検出** — レジストリをリアルタイム監視。EnvStudio の起動中に他のプログラムが環境変数を変更すると、即座に更新通知。
- **プロファイルシステム** — 異なる開発環境向けに変数プロファイル（例：「Java 8」「Node.js」「AI/ML」）の保存、切替、適用が可能。
- **スナップショット＆ロールバック** — 変更のたびに自動スナップショット、Git スタイルの差分表示とワンクリックロールバック。
- **検索とフィルター** — 正規表現でユーザーとシステムスコープ全体を素早く検索。一致した PATH サブエントリは自動展開され、マッチ数バッジを表示。
- **エクスポート** — 変数を PowerShell、Batch、.env ファイル形式でエクスポート。チーム共有やシステム再インストール後の復元に便利。
- **UAC 昇格** — システム変数の編集にシームレスな管理者昇格。
- **即時ブロードキャスト** — `WM_SETTINGCHANGE` で変更をシステム全体に即座に通知。

## 100% オフライン · 完全無料

EnvStudio は**完全にオフラインで動作し、テレメトリーやデータ収集は一切ありません。** 環境変数の設定はお使いの PC にのみ保存されます。

すべての機能が**完全無料**で、広告やペイウォールはありません。将来的に寄付の受付を追加する可能性がありますが、機能が制限されることは一切ありません。

詳しくは[プライバシーポリシー](https://prunelab.net/ja/products/envstudio/privacy)をご覧ください。

---

## フィードバック

> **注意：** 本リポジトリには EnvStudio のソースコードは**含まれておらず**、ユーザーフィードバックと課題管理専用です。

| アクション | リンク |
|------|------|
| バグを報告 | [バグレポートを作成](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=bug_report.yml) |
| 機能を提案 | [機能リクエストを送信](https://github.com/PruneLab/EnvStudio-Feedback/issues/new?template=feature_request.yml) |
| すべての Issue | [Issues](https://github.com/PruneLab/EnvStudio-Feedback/issues) |

## 報告する前に

重複を避けるため、まず[既存の Issue](https://github.com/PruneLab/EnvStudio-Feedback/issues) を検索してください。

バグを報告する際は、以下の情報を含めてください：
- **EnvStudio バージョン**（「設定 → バージョン情報」で確認）
- **Windows バージョン**（例：Windows 11 23H2）
- **再現手順**
- **期待される動作** vs **実際の動作**
- スクリーンショット（あれば）

## 機能のアイデア

アイデアをお聞かせください！投稿前に：
- 同じ提案がすでにないか確認
- ユースケースを説明——その機能はどんな課題を解決しますか？
- モックアップや参考リンクも歓迎します
