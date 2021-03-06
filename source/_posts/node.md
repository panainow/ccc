---
title: Node.jsとは
date: 2019-03-18 16:36:48
tags: Node.js
---

### Node.js
javascriptでプログラミンが出来る、
サーバーサイド向けのプラットフォーム。

※ プラットフォームとは、コンピュータにおいて、ソフトウェアが動作するための土台（基盤）として機能する部分のことである。 プラットフォームとは、そもそも「壇上」や「（高い）足場」といった意味を持つ英語である。 

サーバーサイドに限らず、開発用ツールやディスクトップアプリの開発にも使われている。
例えば、Visual Stuido Codeも。

<!--- more --->

<img src="wow.png" alt="" title="node" width="300">


複数のコアをもつCPUを生かす必要のない処理では、C++,Java等のように高速なプログラミング言語と同等な場合もある。

Node.jsの言語でもあるJavaScriptは、
スクリプト言語であり、開発が容易。

※ スクリプト言語は、プログラムの記述や実行を比較的簡易に行うことができる言語の総称。スクリプト言語はインタープリタ型言語であり、コンパイラ型言語に比べて実行までの処理の手間がかからないという特徴を持っていて、尚且つスクリプト言語はコンパイルがいらない。

※ コンパイルとは、プログラミング言語で書かれた文字列（ソースコード）を、コンピュータ上で実行可能な形式（オブジェクトコード）に変換することです。 コンパイルを行うソフトウェアをコンパイラといい、変換されるプログラミング言語をコンパイラ型言語と呼ぶ。

<img src="globe.png" alt="" title="node" width="300">

では、Node.jsをインストールしていきます。

- Homebrew 
- nodebrew
- Node.js
をインストールしていきます。

 [Homebrew](https://brew.sh/index_ja.html)

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
インストール後の確認方法。
```
$ brew -v
$ Homebrew 2.0.3
$ Homebrew/homebrew-core (git revisionec52; last commit 2019-03-09)
```
nodebrewのインストール
```
$ brew install nodebrew
```
からのVer.確認
```
nodebrew -v
```
あれ？ファイルが見つからない？
んん？

Pathを通す、、、Pathを通す？！、、、ちょっと何言ってるかわかりません。

ので、一旦中断して環境変数とかPathとか理解します。