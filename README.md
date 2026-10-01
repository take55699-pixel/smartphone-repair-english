# スマホ修理受付 英会話 — GitHub Pages公開手順

このフォルダ内のファイルは、そのままGitHub Pagesへ公開できます。

## 1. GitHubで新しいRepositoryを作成
例:
`smartphone-repair-english`

Publicで作成するとGitHub Pagesを無料で使いやすいです。

## 2. このフォルダの中身をRepositoryのルートへアップロード

アップロードするファイル:

- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png
- .nojekyll

`README.md` は公開動作には必須ではありません。

## 3. GitHub Pagesを有効化

Repositoryを開く
→ Settings
→ Pages
→ Build and deployment
→ Source: Deploy from a branch
→ Branch: main
→ Folder: / (root)
→ Save

公開処理が終わると、Pages画面にHTTPSのURLが表示されます。

例:
`https://ユーザー名.github.io/smartphone-repair-english/`

## 4. Android Chromeから開く

公開されたHTTPS URLをChromeで開きます。

数秒待ってから、
- ページ上部の「アプリとしてインストール」
または
- Chromeメニューの「アプリをインストール」「ホーム画面に追加」

を使用します。

## 注意

`content://` や `file://` でHTMLを直接開いた場合はPWAとしてインストールできません。
GitHub PagesのHTTPS URLから開いてください。
