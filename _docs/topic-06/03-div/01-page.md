---
title: The &lt;div&gt; Element
module: topic-06
permalink: /docs/topic-06/div-element/
redirect_from: /docs/topic-06/03-div/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Up till this point, all elements that we have looked at have had specific structural or semantic purposes (i.e. defining a paragraph, heading, emphasized text, or including images). There are however, elements that provide structure, without necessarily implying styling or content.

<div class="container-row">
  <img src="../img/legos-div.png" alt="stacked building blocks" title="Just like building blocks!" style="float: right; width: 150px; margin-top: 0;" />

  <p>The <code>&lt;div&gt;...&lt;/div&gt;</code> element offers developers a <b>block-level element</b> to group other elements together. To describe the example images you've been seeing, these elements work much like building blocks - separate bricks that come together to create the structure of the page.</p>

  <p>This element is heavily used by developers to increase structural clarity and identify element groups. This in turn, increases readability, which is always desired.</p>
</div>

<div id="code-heading">HTML</div>
```html
<div id="one">
  <!-- Content -->
</div>

<div id="two">
  <!-- Different Content -->
</div>
```

This element also serves as an easy way to wrap content to style via CSS. _By itself, the sole styling implied by the_ `div` _element is that it will start on a new line_
