---
layout: post
pubdate: "2012-12-19T23:47:27+09:00"
title: Backlog API の仕様
tags: [clojure]
pagetype: posts
---
[昨日問い合わせた件](/2012/12/18/backlog-api-for-clojure-3/)は、やはり対応してくれなさそう。そりゃそうか。リスクリターン合わないよね。諦めて自作する。

あと5つのタスクが完了すれば 0.2.0 をリリースできる予定。

対応する機能としては、[Backlog API](http://www.backlog.jp/api/)のページに書かれているもののうち、`backlog.admin.*` やマックスプランでのみ動くものを除いたものだ。

APIラッパーがあったところで、何も作らなきゃ意味はないんだけどね。きっとテキストファイルなどを読んで一括で取り込む機能を作ると思う。うん。

6 min.
