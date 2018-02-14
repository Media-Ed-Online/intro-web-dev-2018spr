---
title: Nesting Lists
module: topic-04
permalink: /docs/topic-04/nested-lists/
redirect_from: /docs/topic-04/40-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

You can combine list types as well as use multiple nested list elements to create hierarchically-related lists. This is particularly useful for outlines or multi-part instructions, as examples.

<span class="label label-info">NOTE:</span> Notice how the nested list is contained _within_ the parent "list-item" element.

```html
<ol id="ordered-list">
  <li>Ordered List Item #1.</li>
  <li>Ordered List Item #2.</li>
      <ul id="unordered-list">
          <li>Item A relating to Order List Item #2.</il>
          <li>Item B relating to Order List Item #2.</li>
      <ul>
  <li>Ordered List Item #3.</li>
<ol>
```

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NyvMRY" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: HTML Lists Pt. 4" class="codepen"></p>
</div>
