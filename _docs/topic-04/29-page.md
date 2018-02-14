---
title: Abbreviations and Acronyms
module: topic-04
permalink: /docs/topic-04/abbr-acro/
redirect_from: /docs/topic-04/29-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The **abbreviation** element (`<abbr>...</abbr>`) defines an abbreviation or an acronym, like "Mr.", "Dec.", "ASAP", "ATM".

Marking up abbreviations can give useful information to browsers, translation systems and search-engines.

<span class="label label-info">NOTE:</span> Previous to HTML5, there was an `<acronym>` tag that is no longer supported. Is it best practice to use `<abbr>` for both abbreviations and acronyms in HTML5.

<div id="code-heading">HTML</div>
```html
<p>You can spell out acronyms using the <abbr title=""> tag.</p>
<p>For example, <abbr title="HyperText Markup Language">HTML</abbr>.</p>
```

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="WMEEaL" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: Semantic HTML Pt. 5" class="codepen"></p>
</div>

<span class="label label-info">NOTE:</span> Hover your mouse over the shortened words to see their names expanded.
