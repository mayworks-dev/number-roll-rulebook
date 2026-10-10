# NUMBER ROLL — PLAYABLE RULEBOOK

NUMBER ROLL の障害物1〜10を実際に練習できる、HTML/Canvasの小さなWebアプリです。

## GitHub Pages に公開する

1. GitHubで新しい **Public** リポジトリ `number-roll-rulebook` を作成（READMEは空でも可）。
2. このフォルダの `index.html`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `.nojekyll` をリポジトリのルートにアップロードしてCommitします。
3. リポジトリの **Settings → Pages → Build and deployment → Source: Deploy from a branch** を選び、**Branch: main / (root)** にして保存します。
4. Pagesの公開URL（通常 `https://ユーザー名.github.io/number-roll-rulebook/`）にiPhoneのSafariでアクセスします。
5. Safariの共有メニューで **ホーム画面に追加**、その際 **Webアプリとして開く** を有効にして追加します。そのアイコンから開くとブラウザの上下バーが表示されにくくなります。

> 通常のSafariタブでは上下バーが残ることがあります。iPhoneのWebアプリ化は「ホーム画面に追加」から行います。

## 操作

- タップ：ジャンプ（1回で90度回転）。
- 着地すると、その時点で上を向いている数字に応じてジャンプ回数が回復します。
- PREV/NEXT：障害物を切り替えます。
- リトライ：失敗したコースをすぐやり直します。
- 横画面を推奨します。

実装は単一のHTMLファイルにまとまっており、外部ライブラリは使用していません。アイコンとマニフェストはホーム画面追加のための補助ファイルです。
