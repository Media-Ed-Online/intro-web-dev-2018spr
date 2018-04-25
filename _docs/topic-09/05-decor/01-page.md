---
title: Font Variant
module: topic-09
permalink: /docs/topic-09/font-variant/
redirect_from: /docs/topic-09/05-decor/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are two properties that allow developers to set the capitalization of text. The first is **font-variant**. This property allows developers to specify whether text should appear in all caps, with 'non-capitalized' letters being displayed as small caps.

<div id="code-heading">CSS</div>
```css
* {
  font-variant: normal;
}
```

`font-variant: ` accepts these term values:

- `normal` (default)
- `small-caps` (display small-caps font)


In a small-caps font, all lowercase letters are converted to uppercase letters. However, the converted uppercase letters appears in a smaller font size than the original uppercase letters in the text.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="MGKzzp" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Font-Varient (Toggle)" class="codepen"></p>
</div>

<!--<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="zPYBow" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Caps & Cases, Pt. 1" class="codepen"></p>
</div>-->
