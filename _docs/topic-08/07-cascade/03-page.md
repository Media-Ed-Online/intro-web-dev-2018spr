---
title: Specificity
module: topic-08
permalink: /docs/topic-08/cascade-specify/
redirect_from: /docs/topic-08/07-cascade/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Rules which are more **specific** will take precedence over less specific rules. This is true even if the less specific rule is defined last.

For example;
- `h1 p {}` is more specific than `p {}` alone.
- `.box-two` is more specific than `<div>`.
- `#first-paragraph-id` is more specific than `.box-two`


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="XeGKGd" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-07]  Cascading, Pt. 2" class="codepen"></p>
</div>
