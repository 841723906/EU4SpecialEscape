# EU4SpecialEscape
## これはなに？
　Steam配信されているWindows版Europa Universalis IVの日本語化パッチの副産物です。パッチはこのプログラムを使って変換されたテキストのみを受け付けます。

## 環境
　Windows7 以上

## 使い方
適当なフォルダを用意します。

変換したいテキストが入ったファイルを下記に注意して、上記のフォルダ内に保存してください。フォルダを階層構造にしても良いです。

 - BOM付きのUTF-8
 - ファイル名をxxx.utf8b.yyyにする。xxxは任意の文字列。yyyはa~zとA~Zと0~9とアンダースコア(_)のみ使用可能

上記のフォルダを、ConsoleApplication3.exeにドラッグアンドドロップしてください。フォルダ内に、xxx.yyyとして変換されたテキストが保存されます。

## ビルドの仕方
　VC2015以上でConsoleApplication3.slnを開き、ビルドしてください。

## ライセンス
　MITライセンス