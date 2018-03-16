---
title: Directing Attention
module: topic-07
permalink: /docs/topic-07/html-style-declare/
redirect_from: /docs/topic-07/02-html-style/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

By now, you are familiar with two ways to **select** an "item" to style:
1. By the structural element itself:
    - `body {}` (“Do ___ to the entire body of the page.”)
    - `table {}` (“Do ___ to all tables on the page.”)
    - `p {}` (“Do ___ to all paragraphs on the page.”)
2. By creating classes:
    - `.a-class {}` (“Do ___ to any element with `class="a-class"`.”)
    - `.another-class {}` (“Do ___ to any element with `class="another-class"`.”)

As you can see, _selecting elements_ effects large portions of the page, good for backgrounds, image styling, and text. Creating and _selecting classes_ is good for styling distinct portions of the page, to better differentiate them from each other. We can combine these selections to style elements, both overall and individually.

For example, we can say we want _all_ tables in our site to have black borders 1px wide, but the first table will have orange text, and the second green:


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="OvXmay" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-05: Tables, Pt. 4" class="codepen"></p>
</div>
