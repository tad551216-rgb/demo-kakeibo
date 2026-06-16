# わが家の家計簿 — デモ版

サンプルデータ入りの家計簿アプリ（デモ）です。公開URL `https://tad551216-rgb.github.io/demo-kakeibo/` を開くと、そのまま起動します。

- 初回起動時に、架空の取引（39件）を自動投入します。
- 上部の「サンプルに戻す」でいつでも初期状態に戻せます。
- データはこのアプリ専用のデータベース（kakeibo_demo）に、利用者の端末内だけ保存されます。外部送信はありません。

## 公開方法（GitHub Pages）

このリポジトリ（demo-kakeibo）の**ルート**に、以下の7ファイルをすべて置いてください。

```
index.html
sw.js
manifest.json
icon-180.png
icon-512.png
xlsx.mini.min.js
template_iryouhi.b64.js
```

Settings → Pages → Deploy from a branch（main / root）で公開。`https://tad551216-rgb.github.io/demo-kakeibo/` で直接デモが立ち上がります。
