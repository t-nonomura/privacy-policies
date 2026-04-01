# privacy-policies

複数アプリの Privacy Policy をまとめて公開するための public repository 用構成です。

想定用途:

- GitHub Pages で各アプリの Privacy Policy を公開する
- Google Play などのストア申請で、各アプリごとの Privacy Policy URL を使う

## ディレクトリ構成

- [`index.html`](./index.html): 一覧トップ
- [`assets/site.css`](./assets/site.css): 共通スタイル
- [`overlay-pen/index.html`](./overlay-pen/index.html): overlay-pen 日本語版
- [`overlay-pen/en/index.html`](./overlay-pen/en/index.html): overlay-pen 英語版

今後アプリを追加する場合は、同じ粒度でフォルダを増やします。

例:

- `app-a/index.html`
- `app-a/en/index.html`
- `app-b/index.html`
- `app-b/en/index.html`

## GitHub Pages の推奨設定

- public repo として作成
- `main` ブランチの `/(root)` を公開元に設定

project pages の場合、URL は次のようになります。

- 一覧トップ: `https://<GitHubユーザー名>.github.io/<repo名>/`
- overlay-pen 日本語版: `https://<GitHubユーザー名>.github.io/<repo名>/overlay-pen/`
- overlay-pen 英語版: `https://<GitHubユーザー名>.github.io/<repo名>/overlay-pen/en/`

## 置換が必要なプレースホルダ

overlay-pen のページには次のプレースホルダが入っています。

- `YOUR_PUBLIC_CONTACT_EMAIL`
- `YOUR_OVERLAY_PEN_POLICY_URL`

対象ファイル:

- [`overlay-pen/index.html`](./overlay-pen/index.html)
- [`overlay-pen/en/index.html`](./overlay-pen/en/index.html)

## 次にやること

1. repo 名を決める
2. 公開用メールアドレスを決める
3. `overlay-pen` のプレースホルダを実値に差し替える
4. GitHub Pages を有効化する

詳しい手順は [`SETUP.md`](./SETUP.md) を参照してください。

