---
title: Absolute Position
module: topic-10
permalink: /docs/topic-10/position-absolute/
redirect_from: /docs/topic-10/08-position/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Setting the position property to 'absolute' (`position: absolute;`) allows developers to specify exactly where on a page an element should be located. This can be accomplished using the position properties mentioned above.

Setting an elements position to 'absolute' also has the effect of taking it "out" of the normal flow. This means other elements will not reserve space for this element.

In the following example, the second paragraph is placed 20 pixels from the top and 100 pixels from the left, regardless of what the other elements are doing or where they are positioned. As a result, this paragraph (`.absolute-element`) is positioned "on top" of the other elements.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="bYgZqy" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Position, Pt. 2" class="codepen"></p>
</div>
