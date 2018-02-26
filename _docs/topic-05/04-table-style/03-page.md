---
title: Cell Padding
module: topic-05
permalink: /docs/topic-05/table-padding/
redirect_from: /docs/topic-05/04-table-style/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

You may wish to "cushion" your cell contents from their borders. We do this using the `padding=""` property. Generally, we measure this **padding** in pixels, and again, this is something we'll eventually do with CSS.

<div id="code-heading">HTML</div>
```html
<style>
    table, th, td {
      border: 1px solid black;
      padding: 5px;
    }
</style>
```
