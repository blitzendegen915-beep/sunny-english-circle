# Sunny English Circle — HP試作（公開用ビルド）

0〜2歳児と保護者の親子英語サークル「Sunny English Circle」のホームページ試作。
**クライアント未承認の下書き**であり、確定サイトではない。

## このリポジトリの扱い

- 全ページに `<meta name="robots" content="noindex, nofollow">` を付けている（検索結果に出さないため）
- `images/` の写真のうち `lesson-song.jpg` / `lesson-play.jpg` は、**お子さまの顔のみぼかした加工版**。
  講師のお二人はご本人が素材として提供されたため顔を出している。お子さまの加工前の元画像はこのリポジトリに入れていない
- クライアントのヒアリング情報（社外秘）はこのリポジトリに含めない

## 掲載内容

すべてクライアント提供の原稿・ロゴ・写真にもとづく（2026-08-31 受領）。
申込フォームURL・InstagramURL・メールアドレス・開催日時・会場住所はすべて確定情報。

## 公開前に必要な確認

- **写真に写っているお子さまの保護者の掲載承認**（未取得のため、現在は顔をぼかしている）
- 掲載内容全体のクライアント承認
- 承認後に全ページの `noindex, nofollow` を外す（これを外すまで検索結果には出ない）

## ファイル構成

```
index.html      トップ（ロゴ・写真4枚のクロスフェード・Instagram導線）
about.html      Our lesson レッスンについて／Our mission 私たちの目指すところ
teachers.html   Teachers 講師紹介
access.html     場所・日時・費用・お申し込み／お問い合わせ
images/         ロゴ2点・水彩フレーム・写真6点
.nojekyll       GitHub PagesのJekyll処理を無効化
```

ビルド不要の静的HTML。外部CDN・Webフォント・外部画像への通信は発生しない。
