# 🧅 玉葱品種図鑑 — PWA版

九州・兵庫（淡路島）の玉葱品種図鑑アプリです。
GitHub Pages で公開することでスマホ・PCのホーム画面にアプリとして追加できます。

## ファイル構成

```
/
├── index.html        ← メインアプリ
├── manifest.json     ← PWAマニフェスト
├── sw.js             ← Service Worker（オフライン対応）
├── favicon.ico       ← ブラウザタブのアイコン
└── icons/
    ├── apple-touch-icon.png  (180x180)
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    └── icon-512x512.png
```

## GitHub Pages への公開手順

1. GitHubにログインして新しいリポジトリを作成（例: `tamanegi-zukan`）
2. このフォルダの中身を全部アップロード
3. Settings → Pages → Source: `main` branch → Save
4. 数分後に `https://[ユーザー名].github.io/tamanegi-zukan/` で公開完了

## ホーム画面への追加方法

### iPhone / iPad (Safari)
1. Safariでアプリのページを開く
2. 画面下の共有ボタン（□↑）をタップ
3. 「ホーム画面に追加」→「追加」

### Android (Chrome)
1. ChromeでページURL を開く
2. メニュー（︙）→「アプリをインストール」または「ホーム画面に追加」

### PC (Chrome / Edge)
1. ChromeかEdgeでURL を開く
2. アドレスバー右端のインストールアイコン（⊕）をクリック
3. 「インストール」→ デスクトップにアイコンが追加される
