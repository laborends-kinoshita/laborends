# 合同会社レイバーエンズ 公式サイト

検索エンジンに登録しやすい最小構成の静的サイトです。

## 公開前に変更する場所

- `index.html` の `https://example.com/` を実際のドメインに変更
- `robots.txt` の `Sitemap: https://example.com/sitemap.xml` を実際のURLに変更
- `sitemap.xml` の `<loc>https://example.com/</loc>` を実際のURLに変更
- `index.html` の会社概要、所在地、代表者、事業内容、メールアドレスを実情報に変更

## インデックス登録の基本手順

1. サイトを本番ドメインで公開する
2. Google Search Console にドメインを登録する
3. `sitemap.xml` を送信する
4. Search Console の URL 検査でトップページのインデックス登録をリクエストする
5. `robots.txt` やページ内に `noindex` が入っていないことを確認する

## ファイル構成

- `index.html`: トップページ本体
- `styles.css`: デザイン
- `robots.txt`: 検索エンジン向けのクロール許可設定
- `sitemap.xml`: 検索エンジンへページURLを伝えるサイトマップ
