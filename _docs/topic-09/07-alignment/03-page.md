---
title: Indentation
module: topic-09
permalink: /docs/topic-09/text-indent/
redirect_from: /docs/topic-09/07-alignment/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

**First-line indents** are another typesetting property that CSS allows for the manipulation of. This property is controlled via `text-indent: `.

This property controls how much the first line of a paragraph is indented.

<div id="code-heading">CSS</div>
```css
* {
  text-indent: 0;
}
```

As with many text properties, this once can be passed absolute values with pixels (`px`) or points (`pt`). It can also be passed relative values, such as `em`s.

`text-indent:` accepts these term values:
- `normal` (default, no extra spacing, 0)
- pixels (`px`)
- points (`pt`)
- percent (`%`)
- ems (`em)`
- ...most other size terms, including negative values

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="aGdRYd" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09]  Text Indent (Toggle)" class="codepen"></p>
</div>
