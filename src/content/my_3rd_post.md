Title: My 3rd Post
Date: 2025-09-05
Category: テクノロジー

これは私の３番目の投稿です。
以下は、サイトのビルド方法です。

## サイトの公開手順

このプロジェクトでは、コンテンツをビルドし、GitHubにプッシュすることでCloudflare Pagesに自動でデプロイする流れを想定しています。

### 1. 公開用のサイトをビルド

まず、ローカルで公開用の静的ファイルを生成します。プロジェクトのルートディレクトリで以下のコマンドを実行してください。

```bash
invoke preview
```

このコマンドは `publishconf.py` の設定を使って `src/output` ディレクトリにファイルを出力します。

### 2. 変更をGitHubにプッシュ

次に、生成されたファイルを含むすべての変更をGitHubリポジトリにプッシュします。

```bash
git add .
git commit -m "記事の追加や更新"
git push origin main
```

### 3. Cloudflare Pagesでの自動ビルド

Cloudflare Pagesは、GitHubリポジトリへのプッシュを検知して、自動でサイトのビルドとデプロイを行います。

Cloudflareでのビルド設定は以下の通りです。

*   **ビルドコマンド**: `invoke preview`
*   **ビルド出力ディレクトリ**: `src/output`

この設定により、GitHubにプッシュするだけで、数分後にはサイトが更新されます。

---


