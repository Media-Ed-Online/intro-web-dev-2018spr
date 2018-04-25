---
title: Relative Size
module: topic-09
permalink: /docs/topic-09/relative-size/
redirect_from: /docs/topic-09/03-sizing/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Another approach (and the one often suggested) is to use **relative-size** measurements for font size instead of absolute sizes. These set the font size of an element as a ratio to the parent's font size.

There are a few ways to accomplish this, but we will focus on two:

- percent (`%`)
- ems (`em)`

Both are relatively similar in how they work. A value of `100%` or `1em` will both leave the font size the same as the parent element. Likewise a value of `50%` or `0.5em` will reduce the font size by half.

<span class="label label-info">NOTE:</span> An `em` is described as being the width of the letter 'm'. So 1em is the width of an 'm' in the specified font.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="vWYNRv" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Adding Emphasis, Pt. 7" class="codepen"></p>
</div>
