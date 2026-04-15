# 852 Hz PWA — セットアップ手順

## ファイル構成
```
852hz-pwa/
├── index.html          ← メインアプリ
├── manifest.json       ← PWA設定
├── sw.js               ← Service Worker（オフライン対応）
└── icons/
    ├── icon-192.png    ← アイコン（Android）
    ├── icon-512.png    ← アイコン（大）
    └── apple-touch-icon.png  ← iOSホーム画面アイコン
```

---

## GitHub Pages で公開する手順（無料・5分）

### 1. GitHubアカウント作成
https://github.com にアクセスしてアカウントを作成

### 2. リポジトリ作成
- 右上「＋」→「New repository」
- Repository name: `852hz`（任意）
- Public を選択
- 「Create repository」をクリック

### 3. ファイルをアップロード
- 「uploading an existing file」をクリック
- このフォルダ内のすべてのファイル・フォルダをドラッグ＆ドロップ
  - index.html
  - manifest.json
  - sw.js
  - icons フォルダごと
- 「Commit changes」をクリック

### 4. GitHub Pages を有効化
- リポジトリの「Settings」タブ
- 左メニュー「Pages」
- Source: 「Deploy from a branch」
- Branch: `main` / `/(root)` を選択
- 「Save」

### 5. 公開完了
数分後に以下のURLでアクセス可能になります：
```
https://[あなたのユーザー名].github.io/852hz/
```

---

## iPhoneでホーム画面に追加する方法

1. SafariでURLを開く（Chromeは不可）
2. 画面下の **共有ボタン（□↑）** をタップ
3. **「ホーム画面に追加」** を選択
4. 右上の **「追加」** をタップ

→ ホーム画面に 852 Hz のアイコンが追加され、LINEと同じように起動できます！
