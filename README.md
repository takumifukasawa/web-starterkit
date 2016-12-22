# web-starterkit

npm-scriptsを使ったフロントエンド開発環境

## 環境

* $ yarn (or $ npm install)

## 環境

* $ yarn start (or $ npm start)
  * browser-sync, pug, postcss, watchifyが走ります。

## ファイル構成

* `config/postcss.json`
  * postcssの設定ファイルです
* `config/pug.json`
  * pug用にmeta情報などを記載するjsonです。
* `src/pug`, `src/css`, `src/js`
  * 開発用ディレクトリで、ビルドするのに必要な各ソースが入っています。
* `public`
  * ビルド済みファイルが入っています。

## 各種言語

* html: pug
* js: es6記法
* css: postcss

