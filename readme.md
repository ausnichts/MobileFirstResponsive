# Mobile-First Responsive

Boilerplate をベースにしたはてなブログのデザインテーマです。

はてなブログの必要最小限の見た目が調整されています。このテーマをもとにしてCSSを書くと比較的楽にデザインテーマが作れます。  

# 構成

mobilefirstresponsive.less
mobilefirstresponsive.css

ファイルの概要は下記のとおりです。

* mobilefirstresponsive.less
    * 基本となるスタイルが書かれているLESSファイルです。加えて、下記の4つのLESSファイルを読み込んでいます。
* _mixin.less
    * ミックスインです。主にCSS3でベンダープレフィックスが含まれるプロパティを簡単に記述できるようにしています。
* _variable.less
    * テーマで使っている色に関する変数です。
* _media-queries.less
    * media queries に関するスタイルです。
* _normalize.less
    * <a href="http://necolas.github.com/normalize.css/">normalize.css</a>です。


# ライセンス
 
このCSSおよびLESSファイルはMITライセンスのもと自由に複製・再配布できます。
記事本文の書式やコメント欄のスタイルなど、必要な部分だけをコピーして使ってもかまいません。
このデザインテーマをもとにしたテーマの配布も自由です。