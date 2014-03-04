javascriptDP
============

javascript design pattern study

## 6.1 Pattern

jQueryの短縮記法$が他のライブラリと競合することを防ぐためにjQueryを渡す
$.extendを使う場合


## 6.2 軽量スタートパターン

* 実行前にセミコロンを置く
* window, document, undefinedを引数として渡す
* 基本的なデフォルトオブジェクト
* インスタンスが複数生成されることを防ぐ
etc..

## 6.3 完全なウィジェットファクトリパターン

jQueryUI Widget Factoryは複雑かつステートフルなプラグインをオブジェクト指向で開発するのを助けてくれる。
WidgetFactoryはjQueryUIの土台に使われている点がすぐれている。

## 6.4 入れ子の名前空間プラグインパターン
