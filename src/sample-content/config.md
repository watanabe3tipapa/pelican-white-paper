# このPelican（Pelican White paper）を利用する上での必須設定について

## ⚙️ 設定値

### コンテンツ（マークダウンファイル）に画像を挿入するための設定

- pelicanconf.pyに以下を追記します

```python
STATIC_PATHS = ['assets']
```

 💡 assetsではなく、images などフォルダ名は自由です

- コンテンツ（マークダウンファイル）には次のように画像挿入を記述します

```markdown
![代替テキスト](assets/your_image.jpg)
```

---

### 各種プラグインのて適用

後日追記予定

---


