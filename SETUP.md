# GitHub Pages セットアップ

最終更新日: 2026-04-01

このリポジトリは、複数アプリの Privacy Policy を GitHub Pages でまとめて公開する前提です。

## 1. public repo を作成する

GitHub 上で新しい public repo を作成します。

例:

- `privacy-policies`

## 2. このディレクトリの中身を repo ルートに配置する

`D:\privacy-policies` の中身を、そのまま GitHub repo のルートに置きます。

## 3. overlay-pen の公開 URL を決める

project pages の場合、overlay-pen の日本語版 URL は通常次の形式です。

- `https://<GitHubユーザー名>.github.io/<repo名>/overlay-pen/`

英語版 URL:

- `https://<GitHubユーザー名>.github.io/<repo名>/overlay-pen/en/`

`YOUR_OVERLAY_PEN_POLICY_URL` には日本語版 URL を入れてください。

## 4. プレースホルダを差し替える

overlay-pen 用に次の値を差し替えます。

- `YOUR_PUBLIC_CONTACT_EMAIL`
- `YOUR_OVERLAY_PEN_POLICY_URL`

対象ファイル:

- `overlay-pen/index.html`
- `overlay-pen/en/index.html`

## 5. GitHub に push する

commit / push を行います。

## 6. GitHub Pages を有効化する

GitHub で対象 repo を開き、次を設定します。

1. `Settings`
2. `Pages`
3. `Build and deployment`
4. `Source` を `Deploy from a branch` にする
5. `Branch` を `main` にする
6. フォルダを `/(root)` にする
7. `Save`

## 7. 公開確認

次の URL が開けることを確認します。

- `/`
- `/overlay-pen/`
- `/overlay-pen/en/`

確認ポイント:

- 文字化けがない
- 言語切り替えリンクが動く
- メールアドレスと公開 URL がプレースホルダのまま残っていない

## 8. Google Play に設定する URL

overlay-pen の `Privacy Policy URL` には通常こちらを設定します。

- `https://<GitHubユーザー名>.github.io/<repo名>/overlay-pen/`

アプリ追加時も、各アプリの個別ページ URL をストアに設定します。

