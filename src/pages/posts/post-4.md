---
layout: ../../layouts/MarkdownPostLayout.astro
title: 私の4番目のブログ記事
author: Astro学習者
description: "この記事単独で表示されます！"
image:
  url: "https://docs.astro.build/default-og-image.png"
  alt: "惑星と星のイラストの中にastroという単語があります。"
PubDate: 2022-08-08
tags: ["astro", "成功","成功かわからない！"]
---
記事のリストを作成するために`Astro.glob()`がすべての記事データのリストを返しているので、この記事は他のブログ記事と一緒に表示されるはずです。

`client:visible`は、コンポーネントがページ上に表示されたタイミングで対応するJavaScriptを送信します。  

`client:load`ディレクティブによって、ページがロードされたときにJavaScriptをクライアントに送信して再実行  