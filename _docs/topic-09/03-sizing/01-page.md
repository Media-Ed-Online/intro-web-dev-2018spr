---
title: Setting Size
module: topic-09
permalink: /docs/topic-09/font-size/
redirect_from: /docs/topic-09/03-sizing/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<link rel="stylesheet" href="../ex-files/fonts.css">
<link rel="stylesheet" href="../ex-files/style.css">

As you can imagine, it is important to be able to adjust the **font size** of an element, element type, or the entire page. Fortunately (or unfortunately as you may find out), there are many ways to accomplish this all through the `font-size: ` css property.

In general, this property may be use to set the font size of a page or specific element. You can do so through units of measure that you are likely already familiar with, such as _pt_ (point, `font-size: 12pt`) or _px_ (pixel, `font-size: 16px`).

`font-size:` may pass "fixed-size" declarations or "relative-size" declarations. Depending on how you want the font to perform under certain conditions, you can set as such:

<div class="codepen-embed">
  <div id="code-heading">RENDER</div>
  <div class="ex-display">
    <h1 class="size heading-1">I am <b>21px</b> in size.</h1>
    <h1 class="size heading-2">I am <b>150%</b> in size.</h1>
    <h1 class="size heading-3">I am <b>1.5em</b> in size.</h1>
  </div>
</div>

Let's go over these different methods of sizing!
