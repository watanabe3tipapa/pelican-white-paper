# Pelican White Paper

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-0.1.0-green.svg)

概要

Pelican を使って Markdown を Web に変換することを紹介するリポジトリです。Pelican は Python 製の静的サイトジェネレーターで、ブログやドキュメントサイトを簡単に作成できます。

ホームページ

デモ / 公開ページ: https://watanabe3tipapa.github.io/pelican-white-paper/

主な内容・目的

- Pelican の特徴や利点の解説（静的サイト生成、Markdown サポート、プラグイン/テーマ、国際化など）。
- このリポジトリを使った静的サイト作成の手順例（元 README に記載されているコマンド例を含む）。

このリポジトリに含まれる主なファイル・構成（確認できるもの）

- pyproject.toml（プロジェクト設定、依存関係、バージョン情報を含む）
- src/（コンテンツやテンプレートが格納されているディレクトリ）
- uv.lock（リポジトリ内に存在）
- README.md（このファイル）

要件（pyproject.toml による確認）

- Python: >= 3.11
- 依存関係（pyproject.toml に記載されたもの）:
  - invoke>=3.0.3
  - pelican[markdown]>=4.12.0
  - typogrify>=2.1.0

注意: これらはリポジトリに含まれる pyproject.toml で宣言されている要件です。

リポジトリで示されている手順（元 README に記載されているコマンド例）

以下のコマンド例は元 README の内容を再掲しています。実行環境やツール（例: uv）のセットアップ方法はこのリポジトリ内で明示されていないため、実行する場合は各自の環境に合わせて確認してください。

通常のインストール方法（元 README の記載）

（仮想環境でインストールする：推奨）

```bash
uv tool install "pelican[markdown]"
```

依存関係の追加（元 README の記載）

```bash
uv add typogrify
```

プロジェクトの初期化（元 README の記載）

プロジェクト・ディレクトリ（/src）を作ります。

本来のインストール方法
/srcで次のコマンドを実行します

```bash
pelican-quickstart
```

このリポジトリを利用する場合（元 README の記載）

- このリポジトリをクローンします。

当該プロジェクトのディレクトリで次を実行します
（uvが導入されていることを前提にしています）

```bash
uv sync
```

コンテンツ作成とビルド（元 README の記載）

- /src/templates にあるマークダウンファイルの記法を参考にし、作成したコンテンツは /src/content に格納するとされています。

Pelican でマークダウンを変換（元 README の記載）

/src で次のコマンドを実行します

```bash
pelican content
```

プレビュー（元 README の記載）

```bash
pelican --listen
```

注記

- 上記のコマンド群は元 README に記載されている例を整理して示したものです。リポジトリ内のファイルや設定に依存しますので、実行前に環境と設定を確認してください。
- 元 README 内には "uv" による操作例が含まれていますが、uv ツールの導入や挙動はこのリポジトリ内で明示されていません。uv を使う場合は別途ドキュメントを参照してください。

参考資料

- Pelican のドキュメント: https://docs.getpelican.com/en/latest/

ライセンス

- MIT License（元 README に記載あり）

貢献

- 元 README ではプルリクエストやイシューの報告を歓迎すると記載されています。具体的な貢献ガイドラインはリポジトリ内に明記されていないため、貢献を希望する場合はまず Issue を立てるか、プルリクエストを作成してください。

リリース履歴（元 README による）

v0.1.0
- 初期リリース
- Pelican の紹介
- starter kit（README.md）
- pyproject.toml

更新情報

- 最終更新（リポジトリメタデータ）: 2026-08-21T16:21:53Z
