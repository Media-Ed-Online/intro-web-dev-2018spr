---
title: Tracking
module: topic-09
permalink: /docs/topic-09/tracking/
redirect_from: /docs/topic-09/06-spacing/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

**Tracking** is the consistant degree of space between characters.

<img src="../img/typography-tracking.jpg" style="height: 200px; margin: auto" alt="tracking" title="tracking"/>

To adjust the amount of space between characters in CSS, use the `letter-spacing: ` property.

<div id="code-heading">CSS</div>
```css
* {
  letter-spacing: normal;
}
```

`letter-spacing:` accepts these term values:
- `normal` (default, no extra spacing)
- pixels (`px`)
- points (`pt`)
- percent (`%`)
- ems (`em)`
- ...most other size terms, including negative values

As with `line-height: `, this property can be passed absolute values, the word `normal` to use the default, and relative values. When using relative values, be aware that _ems_ will be in relation to the font itself, and _percentages_ will be in relation to the parent element.


### “Why adjust letter spacing?”

It is sometimes useful to space characters out. However, most of the time, this quality can be used to achieve visual text effects for branding, delineating sections, or to make a particular piece of content stand out.

<span class="label label-info">NOTE:</span> Negative values are valid, and can be used to create a "tighter" presentation of text.


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gzaddW" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Tracking (Toggle)" class="codepen"></p>
</div>
