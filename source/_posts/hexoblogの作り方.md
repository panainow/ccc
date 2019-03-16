---
title: hexoblog
date: 2019-03-14 13:07:16
tags: Hexo
---
#### hexoでブログを始める
全くの初心者なので細かいとこは
後から修正していく予定。
まずは実際に試して進めていきます。
	
ターミナルを使います。

<img src="terminal.jpg" alt="" title="hexoblog" width="400">

コレですね。

それでは、実際に作成していきます。
ローカルでブログ用のディレクトリを作成し、インストールします

<!--- more --->
```
npm install -g hexo-cli
```

空のディレクトリを作成し、そこで

```
hexo init
```


します。


```
npm install
```

これですでにローカルに出来上がり。

```
hexo s
```

http://localhost:4000  で確認できます。


<img src="GitHub.jpg" alt="" title="hexoblog" width="800">

＋をクリックしポップアップからNew repositoryを選択

<img src="create_new.jpg" alt="" title="hexoblog" width="800">


Repository name のところに好きな名前　(最初、ローカルに作成したディレクトリの名前で可)
を入力する。

こちらをクリック　<img src="push.jpg" alt="" title="hexoblog" width="200"> 


<img src="front.jpg" alt="" title="hexoblog" width="800">


この画面で一度、ターミナルに戻り、先ほど作成したディレクトリで

```
git init
git add .
git commit -m "作成"
```

<img src="setup.jpg" alt="" title="hexoblog" width="800">

これをコピーしてきて
```
git remote add origin git@github.com:panainow/uuu.git
```

```
git push -u origin master
```
ここまでコマンドを入力したらもう一度、GitHubに戻り、



画面が変わっていることを確認。

<img src="up.jpg" alt="" title="hexoblog" width="800">

### Netlify　に移動

<img src="netlifytop.png" alt="" title="hexoblog" width="800">


他にもいろいろありますが、Netlifyを
わたしは選択。
登録は特に問題なく進んだので省きます。

ログインできたら
<img src="netlify.jpg" alt="" title="hexoblog" width="800">
<img src="newsite.jpg" alt="" title="hexoblog" width="400">
New site from Gitをクリック

あとはサイトの名前を好きなように変更
して大体終了です。
`Site setting`
から
`Change Site name`

独自ドメインに変更はまた今度。



