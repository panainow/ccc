---
title: JavaScriptで時刻を表示してみる
date: 2019-03-22 10:23:40
tags: JavaScript
---
##### 現在時刻を調べる

Javascriptのきほんを学ぶ
HTMLの機能だけではwebユーザがwebページを開いた時刻を
表示することは出来ません。基本的には。
なので、JavaScriptを使います。

<img src="time.png" alt="" title="JavaScriptで時刻を表示してみる" width="1200">

jikoku.html
```
<iDOCTYPE html>
    <html lang="ja">
        <head>
            <meta charset = "utf-8">
            <title>タイトル</title>
        </head>
            <body>
                <script type = "text/javascript">
                    var d = new Date();
                    document.writeln(d)
                </script>
            </body>
    </html>
```

<!--- more--->
<img src="jikoku.png" alt="" title="JavaScriptで時刻を表示してみる" width="1200">