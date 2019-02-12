Web FrontEnd Package for LP
====

LP(ランディングページ)を作るためのwebpackパッケージです。

## Description
パッケージの中身は以下のとおりです。  

- Pug
- Sass
- Babel
- ESLint
- 51.2KB未満の画像ファイルはDataUrl形式で埋め込み
- ビルド時にURL関数の値を絶対URLに書き換え
- ビルド時にdistフォルダを自動クリーンアップ
- フォントのバンドル

このパッケージに好みのJSライブラリやCSSフレームワークを組み合わせるといいと思います。

## Requirement
当パッケージを使うにはNode.js(npm)のインストールが必要です。  
<a href="https://nodejs.org/ja/" target="_blank">Node.jsの公式ページ</a>

## Usage
```
$ npm run start # webpack-dev-serverが起動。こちらで開発します。
$ npm run build # 公開用データをdistフォルダに生成します。
```

## Install
ファイルをダウンロードしたら、以下のコマンドでインストールしてください。
```
$ npm install
```