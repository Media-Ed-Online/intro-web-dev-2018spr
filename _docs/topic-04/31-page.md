---
title: Definitions
module: topic-04
permalink: /docs/topic-04/definitions/
redirect_from: /docs/topic-04/31-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The first use of a new term in a document usually warrants a **definition** tag, `<dfn>`.

The nearest parent of the `<dfn>` tag must also contain the definition/explanation for the term inside the definition tag. Definition tags can also be linked to a related list of terms elsewhere on the page or site.

<div id="code-heading">HTML</div>
```html
<p>The element <def title="definition of term">term</def> is a common way of defining terms.</p>
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="VQzrEY" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: Semantic HTML Pt. 7" class="codepen"></p>
</div>

<span class="label label-info">NOTE:</span> Hover your mouse over the terms to see their definitions expanded.
