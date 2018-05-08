---
title: The Box Model
module: topic-10
permalink: /docs/topic-10/box-model/
redirect_from: /docs/topic-10/01-box-size/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/box-model-full.gif" alt="the full css box model" style="width: 350px; margin: 0 auto 30px;" />

We can "draw" boxes with very minimal coding:

<div id="code-heading">CSS</div>
```css
.my-box {
  width: 100px;
  height: 50px;
}
```

This will give us an area to contain content (say color or text) 100px wide by 50px high, but little else. We cannot control placement, cushion, or relationship to other boxes without giving the stylesheet more information.

In HTML and CSS, we imagine elements as boxes with certain properties. Specifically, every block element in HTML has **padding**, a **border**, and **margin**. This is known as “The Box Model.”

We will go over the tricks and trades of the “box model” over this topic, as well as other techniques you can use to control the appearance of your content.
