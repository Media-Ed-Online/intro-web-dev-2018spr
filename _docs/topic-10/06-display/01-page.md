---
title: What You See...
module: topic-10
permalink: /docs/topic-10/display-intro/
redirect_from: /docs/topic-10/06-display/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/box-model-display.gif" alt="changing display values" style="width: 350px; margin: 0 auto 30px;" />

Up until this point, we have relied upon an element's default value of being _inline_ or _block-level_ to define whether it would be presented next to other elements horizontally or placed beneath previous elements in a new "block".

When not addressed, the default behavior of block-level elements (like `<div>`, `<p>`, `<li>`, etc) is for them to generate as chunks of content linearly down the page. This is what keeps two paragraphs from running into each other, for example. However, there are many times we may _want_ elements to relate differently. We can change this with the **display** property.

<div id="code-heading">CSS</div>
```css
div {
  display: ;
}
```
