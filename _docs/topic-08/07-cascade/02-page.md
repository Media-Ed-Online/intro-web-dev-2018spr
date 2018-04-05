---
title: Order
module: topic-08
permalink: /docs/topic-08/cascade-order/
redirect_from: /docs/topic-08/07-cascade/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The first cascading rule can be referred to as "**order**," or "the last rule."" Essentially, if two or more selectors are the same, than the last one will take precedence.

In the following example, the second rule overwrites the aspects duplicated in the first (i.e. the border specification applies from the first rule, but the color and background-color specs are overwritten).

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="vePKWJ" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-07]  Cascading, Pt. 1" class="codepen"></p>
</div>


## Why?

This may seem like a funny idea right now that may lead to poorly written code. However, it is common for a developer to use pre-made CSS "frameworks" that they load in as separate documents. They may then want to customize their site by overwriting specific rules. Rather than try to change the declarations, they will create a new CSS document, that keeps track of their specific changes and rules. To ensure these rules take precedence, the developer then simply needs to load in their sheet last.

<span class="label label-danger">IMPORTANT:</span> In the following example, three documents are brought in, but notice that the developer's _(mine)_ is brought in **last**.

<div id="code-heading">HTML</div>
```html
<head>
  <link rel="stylesheet" href="https://www.example.com/reset.css">
  <link rel="stylesheet" href="./css/bootstrap.css">
  <link rel="stylesheet" href="./css/my-custom-style.css">
</head>
```
