# Pelican White Paper

## Pelican を使って Markdown を web にしてみましょう


---

## 🐍 Pelican とは

Pelicanは、Pythonで書かれた静的サイトジェネレーターで、ブログやドキュメントサイトを簡単に作成することができます。


## 🚀 主な機能

- リアクティブプログラミング: セルを実行すると、Marimoはそのセルに依存する他のセルを自動的に実行します。これにより、手動でセルを再実行する必要がなくなり、エラーを防ぎます。
- Gitフレンドリー: ノートブックはプレーンなPythonファイル（.py）として保存されるため、Gitによるバージョン管理が容易です。これにより、変更点の追跡や管理がしやすくなります。
- インタラクティブUI要素: スライダーやドロップダウンなどのUIコンポーネントを使用して、ユーザーインタラクションを可能にします。これらの要素は、関連するセルに値の変更を伝播し、結果を動的に更新します。
- AI支援コード補完: GeminiやOllamaなどの大規模言語モデルを利用したコード補完機能があり、開発者の生産性を向上させます。
- SQLとの統合: Pythonの変数に依存するSQLクエリを作成し、データフレームやデータベースに対して実行できます。

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
