---
layout: post
pubdate: "2012-09-10T23:28:03+09:00"
title: Jekyllのpermalinkオプションのprettyに気づく
tags: [jekyll]
pagetype: posts
---
今日、お昼休みにJekyllのソースコードを追っていたら、permalinkオプションの存在に気づく。

そもそもpermalinkというのはpermanentなlinkのことで、そのまま読むと永続的なリンク、検索結果のような一時的なページじゃないよ、ずっとここにあるページだよ、ブックマークしたりするならここにしてね、とそういうURLのことだ。

Jekyllのpermalinkオプションはこのpermalinkの形式を設定するオプションである。いままでは既定値の`date`を使っていた。これは`yyyy/mm/dd/title.html`の形式で、ぼくは前からこのURLが好きじゃなかった。`.html`の部分が冗長だと感じていた。今日ソースコードを読んでいて、このオプションに`pretty`を指定できることに気づいた。

`pretty`を指定するとpermalinkを`yyyy/mm/dd/title/`の形で生成してくれる。ずっとシンプルなURLだ。冗長な`.html`がなくなった。これはうれしい。

うれしいことばかりじゃない。これまでブックマークされてきたものや、リンクされてきたものはおそらくリンク切れになってしまう。これはかなしいことだ。引っ越したことを通知するように残す手もあるが、面倒なのでもう諦めることにする。今日アクセス解析を見て、ほとんど自分しかアクセスしていないことに気づいたし、なんだか投げやりな気持ちである。

今後は満足の行くURLになるのだから、なんでも良い。ああ、明日も仕事だ。

13 min.
