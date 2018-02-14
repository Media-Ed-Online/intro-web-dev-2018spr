---
title: Quotes
module: topic-04
permalink: /docs/topic-04/quotes/
redirect_from: /docs/topic-04/28-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are two common ways of marking up quotations in HTML: quote (`<q>...</q>`) and blockquote (`<blockquote>...</blockquote>`).

The **quote** tag defines a short quotation. Browsers normally _insert quotation marks_ around the quotation.

The **blockquote** tag specifies a section that is quoted from another source. Browsers usually _indent_ blockquote elements.

<div id="code-heading">HTML</div>
```html
<q>This is an quote element, good for keeping quotes inline with other paragraph text.</q>

<blockquote>
  Sometimes a quote spans multiple sentences or lines.<br/>
  Longer quotes are better served in a blockquote element.
</blockquote>
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gvxRqL" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: Semantic HTML Pt. 4" class="codepen"></p>
</div>
