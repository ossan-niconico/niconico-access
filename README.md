# niconico-access

運営者（ossan_niconico）が、自分の YouTube チャンネルの数字を自分の PC で読むための、個人用の道具です。
ほかの人には配っていません。

## できること

- 運営者が許可したチャンネルの、登録者数・視聴回数・総再生時間・動画の一覧・予約した動画の公開日時を読みます。
- 使う API は YouTube Data API と YouTube Analytics API です。
- 読むだけです。動画の投稿・変更・削除や、コメントなどの書き込みはしません。

## プライバシーポリシー

### 取得する情報

運営者が許可したチャンネルについて、次の情報だけを取得します。

- チャンネルの統計（登録者数・視聴回数など）
- 動画の題名・公開の状態・公開日時
- アナリティクスの数字（視聴回数・総再生時間・登録者の増減）

使う許可の範囲は `youtube.readonly` と `yt-analytics.readonly` の2つで、どちらも読み取りだけです。

### 使い方と保存

- 取得した数字は、運営者の PC の記録（CSV）に保存し、運営者だけが見ます。
- 許可のトークンは、運営者の PC の中だけに保存します。
- 第三者には渡しません。広告や AI の学習にも使いません。

### 許可の取り消し

Google アカウントの「サードパーティ製のアプリとサービス」（https://myaccount.google.com/connections）から、いつでも許可を取り消せます。

### お問い合わせ

このリポジトリの Issues からお願いします。

## Privacy Policy (English summary)

niconico-access is a personal, read-only tool used only by its developer to read statistics of the developer's own YouTube channels (scopes: `youtube.readonly`, `yt-analytics.readonly`).
Data is stored only on the developer's own computer and is never shared with third parties, used for advertising, or used to train AI models.
Access can be revoked at any time at https://myaccount.google.com/connections.

niconico-access's use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.
