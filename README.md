# Honoka

[![The MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

[https://tamaina.github.io/Chen/]https://tamaina.github.io/Chen/)

[![Chen](assets/img/sample.png)](https://tamaina.github.io/Chen/)

"Chen" は日本語も美しく表示できるBootstrapテーマです。

## About "Chen"

通常の[Bootstrap](http://getbootstrap.com/)では、日本語のフォント指定や文字サイズは最適とはいえません。"Chen"のベースとなった["Honoka"](honokak.osaka)は、そんなBootstrapをベースに、日本語表示に適したフォント指定や、文字サイズに関するコードを追記したBootstrapテーマの一つです。

"Chen"では、"Honoka"の改良に加え、WebFontを付加しました。

## Live Demo

 * [https://tamaina.github.io/Chen/bootstrap-ja.html](https://tamaina.github.io/Chen/bootstrap-ja.html) (日本語レイアウト)
 * [https://tamaina.github.io/Chen/bootstrap.html](https://tamaina.github.io/Chen/bootstrap.html) (英語レイアウト)

## Getting Started

### Download

[Releases](https://github.com/tamaina/Chen/releases)から最新版をダウンロードしてください。

### Bower

[Bower](http://bower.io/)からインストールすることができません。対応は未定です。

## Usage

Chenは単なるBootstrapテーマにしか過ぎないため，基本的な使い方は本家Bootstrapとほとんど変わりません。よって以下に書くことは[本家Bootstrap](http://getbootstrap.com/getting-started/)からの引用，もしくはその一部を変更したものです。用意されたCSSクラスやコンポーネントなど，より詳細な使い方のドキュメントは本家Bootstrapの各種リファレンスページをご覧になることを推奨します。

 * [CSS](http://getbootstrap.com/css/)
 * [Components](http://getbootstrap.com/components/)
 * [JavaScript](http://getbootstrap.com/javascript/)

### Package

配布しているzipファイルの内容物は以下のとおりです。``bootstrap.min.*``といったように，ファイル名に``min``がつくファイルは，改行やインデント・スペーシングをなくした(minifyされた)コードで，ユーザがウェブページを読み込む際の転送量を少なくすることができます。通常はこの``bootstrap.min.*``を使うことをおすすめします。

```
master/
├─ index.html
├─ bootstrap.html
├─ bootstrap-ja.html
├─ README.md (このファイル)
├─ css/
│   ├─ bootstrap.css
│   └─ bootstrap.min.css
├─ fonts/
│   ├─ glyphicons-halflings-regular.eot
│   ├─ glyphicons-halflings-regular.svg
│   ├─ glyphicons-halflings-regular.ttf
│   ├─ glyphicons-halflings-regular.woff
│   └─ glyphicons-halflings-regular.woff2
└─ js/
     ├─ bootstrap.js
     └─ bootstrap.min.js
```

### Basic Template

Bootstrapをつかってウェブページを作成する際に基本となるHTML部分は以下のようになります。CSSやJavaScriptのファイルパスは環境に合わせて変更する必要があります。

```html
<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>Bootstrap 101 Template</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
  </body>
</html>
```

### Do you hate WebFont?

WebFontを利用したくない場合は、fork元の[Honoka](honokak.osaka)をご利用ください。

[このあたりでWebFontを軽くする(見せる)方法を紹介してたりします。](https://tamaina.github.io/The-Japanese-Web-Fonts/#!HowToSet.md)

## License

[MIT License](LICENSE)

## Author

 * tamaina ([tamaina.github.io](https://tamaina.github.io/))
 * windyakin ([windyakin.net](http://windyakin.net/))
