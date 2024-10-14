Astroを使ったWebサイトのレイアウトテンプレート。

## サンプルサイト
[https://astro-template-layout.pages.dev/](https://astro-template-layout.pages.dev/)

## 要件
- Astro
- React
- Tailwind CSS
- shadcn/ui
- React Icons

## 機能
- 基本レイアウト（Base Layout）
- SEO
- OGP
- Twitter Card
- サイトマップ
- robots.txt
- RSS
- View Transition
- ビューポートが375px未満での表示倍率の縮小（Adjust Viewport）
- スムーススクロール
- Cloudflare Pagesへのデプロイ

## Astroのインストールでテンプレートとして利用する方法
プロジェクトフォルダ内で以下のコマンドを実行する。
```
npm create astro@latest . -- --template Shoirhi/astro-template-layout
```
質問は以下のように回答する。
- Do you plan to write TypeScript? : Yes
- How strict should TypeScript be? : Strict
- Install dependencies? : Yes
- Initialize a new git repository? : Yes

## OGPの設定について
以下のサイトを参照する。
[https://ogp.me/](https://ogp.me/)

### OGP画像の大きさ
横1200px縦630pxのJPEGもしくはPNGで作成する。

## Faviconの生成について
以下のサイトでFavicon画像を生成する。
[https://realfavicongenerator.net/](https://realfavicongenerator.net/)

## 本番環境デプロイ時の注意
環境変数`NODE_ENV`に`production`を追加すること。

## 設定ファイルについて
`/src/config.ts`が設定ファイルとなっている。