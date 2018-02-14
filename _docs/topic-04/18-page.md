---
title: Link
module: topic-04
permalink: /docs/topic-04/head-link/
redirect_from: /docs/topic-04/18-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The _link_ element tells a browser about other resources that the page may need to load. Typically, these are the **CSS** or "style sheets" which dictate how a page will appear in a browser.

We will not use this element for the first few weeks, but will rely upon it for the remainder of the semester after we start with CSS.

<span class="label label-info">NOTE:</span> This element only requires an opening tag, as all information for the element is contained as attributes within the opening tag. This is another example of an "**empty element.**"

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="description" content="Head Elements in HTML">
    <meta name="author" content="Justine Evans">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Way-Cool Awesome Site</title>
    <link rel="stylesheet" href="./css/style.css">
  </head>

</html>
```
