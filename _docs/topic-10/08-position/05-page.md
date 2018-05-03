---
title: Fixed Position
module: topic-10
permalink: /docs/topic-10/position-fixed/
redirect_from: /docs/topic-10/08-position/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Setting an element to "fixed position" (`position: fixed;`) is similar to using "absolute position" in that the position is in relation to the browser, instead of any parent elements. Unlike absolute position though, fixed position is in relation to the "viewable" portion of the browser. This means, that even when you scroll, an element set to "fixed" will remain viewable in the browser window.

This property can be used for "sticky" headers or other elements that you want always visible to the user.

Notice in the following example, that when you scroll, the "fixed element" stays put.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="eegXxR" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Position, Pt. 3" class="codepen"></p>
</div>
