---
title: Dealing with Spills
module: topic-10
permalink: /docs/topic-10/overflow-intro/
redirect_from: /docs/topic-10/02-overflow/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/box-model-overflow.gif" alt="example of overflow scrolling" style="width: 350px; margin: 0 auto 30px;" />

We saw an example on the <a href="./../box-sizing#combine-size" target="_blank">combing size types</a>, where the text inside an element "overflowed" its containing box. We can choose to address this situation in a couple of ways:

1. Ignore it (boo!).
2. Resize our elements so they fit the content.
3. Tell the browser what to do with _extra_ content.

In the latter option, we will use the "overflow" CSS property (`overflow: `). This property takes one of three values:

- `visible`; this is the default.
- `hidden`; overflow content will be hidden.
- `scroll`; scroll bars will be provided for overflow content.
