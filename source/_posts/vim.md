---
title: vimtutor
date: 2019-03-21 02:16:08
tags: vi
---

#### vimtutorを覚えたい

プログラマー目指すなら使い方を覚えて損はないという
CUIのエディタ`vi`をとりあえず触ってみた

基本操作方法だけ

<!--- more --->

<img src="vim-start.png" alt="" title="vimtutor" width="800">


```
$ vimtutor
```
<img src="pressenter.png" alt="" title="vimtutor" width="800">

Press Enter 。。。即、始まっちゃいますね。
何も知らずに始めちゃうとパニックになるかもしれないので、
先ずは、

##### vimでファイルを閉じる

ファイルを開いてる状態で<kbd>esc</kbd>を押して
```
:q
```
と入力。下段に表示されます。
- 「！」をつけると編集内容を破棄して終了。
```
:q!
```
##### ファイルの作り方

目的のディレクトの中に移動。
```
$ vim sample.txt
```
テキスト作成した状態
```
:w
```
wはwriteの略で「書き込み可の状態」
<kbd>i</kbd>か<kbd>a</kbd>キーを押すことで
インサートモード「編集可の状態」
iはinsert（挿入）
aはappend（追加）

テキストを入力して<kbd>esc</kbd>キーで
インサートモード　→　コマンドモードに戻る


つづく　。。。
