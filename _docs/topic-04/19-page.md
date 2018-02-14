---
title: Style
module: topic-04
permalink: /docs/topic-04/head-style/
redirect_from: /docs/topic-04/19-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The _style_ element allows for simple style definitions to be established in a single HTML page without having to link to external documents. This is another element we will not use for the first few weeks but will rely upon heavily after we start looking at CSS.

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
    <style>
      body {background-color: snow}
      h1 {color: purple}
    </style>
  </head>

</html>
```
