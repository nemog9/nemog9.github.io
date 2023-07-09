---
author: nemog
pubDatetime: 2023-07-09T15:22:00Z
title: 最初の投稿
postSlug: test1
featured: false
draft: false
tags:
  - test
ogImage: ""
description: 一番最初の投稿です
---

YouTube 埋め込み

rehype でどうにかしようと思いましたが、面倒で iframe そのまま入れてます。
class 付与してスマホで見てもはみ出ないようにだけしてます。

```html
<iframe
  class="youtube"
  width="560"
  height="315"
  src="https://www.youtube.com/embed/4wEjsUuwQzM"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
></iframe>
```

```css
.youtube {
  margin: 1rem 0;
  aspect-ratio: 16 / 9;
  width: 100%;
  max-width: 680px;
  height: auto;
}
```

<iframe
  class="youtube"
  width="560"
  height="315"
  src="https://www.youtube.com/embed/4wEjsUuwQzM"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
></iframe>
