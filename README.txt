推しglow 美リンパ CMS対応サイト

【GitHub】
このフォルダの中身をすべて新規リポジトリ直下にアップロードしてください。

【Cloudflare】
GitHubリポジトリを接続。
ビルドコマンド: npm run build
デプロイコマンド: npx wrangler deploy
ルートディレクトリ: /
wrangler.jsonc が _site を公開します。

【Pages CMS】
リポジトリをPages CMSに接続すると「お知らせ・ブログ」が表示されます。
.pages.yml はリポジトリ直下に置いてください。

【公開後】
src/sitemap.njk と src/robots.txt の https://oshiglow.workers.dev を実際の公開URLに置き換えるとSEO設定が完成します。
