# Pelican White Paper

## Pelican を使って Markdown を web にしてみましょう


---

## 🐍 Pelican とは

Pelicanは、Pythonで書かれた静的サイトジェネレーターで、ブログやドキュメントサイトを簡単に作成することができます。


## 🚀 主な機能

Pelicanは、Pythonで書かれた静的サイトジェネレーターで、特にブログやドキュメントサイトの作成に適しています。以下に、Pelicanの主な特徴を詳しく解説します。

### 1. 静的サイト生成

- **高速なパフォーマンス**: Pelicanは静的なHTMLファイルを生成するため、サーバーの負荷が軽く、ページの読み込みが非常に速いです。
- **セキュリティ**: 静的サイトは動的なコンテンツを持たないため、データベースやサーバーサイドの脆弱性が少なく、セキュリティが向上します。


### 2. Markdownサポート

- **シンプルな記法**: PelicanはMarkdown形式でコンテンツを作成できるため、書きやすく、視覚的にもわかりやすいです。Markdownは、テキストを簡単にフォーマットできる軽量マークアップ言語です。
- **拡張性**: Markdownの拡張機能を利用して、画像やリンク、リストなどを簡単に追加できます。


### 3. プラグインとテーマのカスタマイズ

- **豊富なプラグイン**: Pelicanは多くのプラグインをサポートしており、SEO、ソーシャルメディアの統合、サイトマップの生成など、機能を簡単に拡張できます。
- **テーマの選択肢**: Pelicanには多くのテーマがあり、デザインを簡単に変更できます。自分でテーマを作成することも可能です。


### 4. 多言語対応

- **国際化**: Pelicanは多言語サイトの構築をサポートしており、異なる言語でコンテンツを作成することができます。これにより、グローバルなオーディエンスに対応できます。


### 5. コマンドラインインターフェース

- **使いやすいCLI**: Pelicanはコマンドラインから操作できるため、スクリプトや自動化ツールと組み合わせて使用することが容易です。ビルドやデプロイを簡単に行えます。


### 6. GitHub PagesやNetlifyとの統合

- **簡単なデプロイ**: Pelicanで生成した静的サイトは、GitHub PagesやNetlifyなどのホスティングサービスに簡単にデプロイできます。これにより、手間をかけずにサイトを公開できます。


### 7. カスタマイズ可能な設定

- **設定ファイル**: `pelicanconf.py`ファイルを通じて、サイトの設定を柔軟にカスタマイズできます。サイト名、URL、テーマ、プラグインなどを簡単に変更できます。

Pelicanは、これらの特徴により、特に開発者や技術者にとって使いやすく、効率的な静的サイトの構築を可能にします。


---

### 📦 通常のインストール方法

Pelicanをインストールするには、以下のコマンドを使用します。
（仮想環境でインストールする：推奨）

```bash
uv tool install "pelican[markdown]"
```
または、推奨される依存関係を含めてインストールするには：
```bash
uv add typogrify
```

プロジェクト・ディレクトリ（/src）を作ります。

本来のインストール方法
/srcで次のコマンドを実行します
```bash
pelican-quickstart
```

---

### 📦 このリポジトリを利用する場合

- このリポジトリをクローンします。

当該プロジェクトのディレクトリで次を実行します
（uvが導入されていることを前提にしています）

```bash
uv sync
```

---

### 📦 コンテンツ（Markdownファイル）を作成

- /src/templatesにあるマークダウンファイルの記法を参考にしてください。
  
作成したコンテンツは/src/contentに格納します



### 📦 pelican でマークダウンを変換

/srcで次のコマンドを実行します
```bash
pelican content
```

### 📦 プレビューしてみます

```bash
pelican --listen
```

---

### 📓 Pelican を学ぶ

[Pelicanのドキュメント](https://docs.getpelican.com/en/latest/)


---
ライセンス

MIT License

貢献

プルリクエストやイシューの報告を歓迎?します！

更新履歴

v0.1.0

- 初期リリース
- Pelican の紹介
- starter kit （README.md）
- pyproject.toml

---

<svg xmlns="http://www.w3.org/2000/svg" width="200" height="50" viewBox="0 0 200 50">
  <a href="https://github.com/watanabe3tipapa/pelican-white-paper" target="_blank">
    <rect width="200" height="50" rx="10" fill="#24292e"/>
    <text x="50%" y="50%" alignment-baseline="middle" text-anchor="middle" fill="#ffffff" font-size="20" font-family="Arial">GitHub Repository</text>
  </a>
</svg>


---
