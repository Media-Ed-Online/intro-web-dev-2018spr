---
title: Relative Position
module: topic-10
permalink: /docs/topic-10/position-relative/
redirect_from: /docs/topic-10/08-position/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Setting the position property to "relative" (`position: relative;`) allows developers to specify an amount off of the normal flow position. Rather, when an element is set to relative, it will still follow normal flow, but can be moved, relative to that position.

**NOTE:** This does not effect the position of surrounding elements. These other elements will continue to be positioned where they would in normal flow. This is true even if the altered element is positioned over them.

In the below example, notice how the `top:` and `left:` properties are used to move the second paragraph to the lower-right of where its
normal flow" position would have been.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="mqRoEj" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Position, Pt. 1 " class="codepen"></p>
</div>
