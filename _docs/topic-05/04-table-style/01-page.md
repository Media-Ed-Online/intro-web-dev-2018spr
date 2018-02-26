---
title: Styling
module: topic-05
permalink: /docs/topic-05/table-style/
redirect_from: /docs/topic-05/04-table-style/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

We can also add visual interest to tables to help with easier reading and showcasing of data. We do this with the **style element**.

_Remember?_ [Last topic](../../topic-04/head-style), we looked at adding _style_ to HTML in the document's `<head>`, via the `<style>...</style>` element.

We can reference the individual elements of the table as a group for easier styling. We do this by separating the elements by commas in the same line of code. Everything in this string will be affected by the styling described between `{}`.

<span class="label label-info">NOTE:</span> Ideally, this is something you'll do in a stylesheet when we get to CSS.


<div id="code-heading">HTML</div>
```html
<head>
  <style>
      table, th, td {
        /* Attributes that will "decorate" the table: */
      }
  </style>
</head>

<body>
  <table>
    <!-- Table contents to-be-styled: -->
  </table>
</body>
```
