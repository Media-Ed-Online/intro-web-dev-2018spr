---
title: Adding Style
module: topic-07
permalink: /docs/topic-07/basic-nav-styling/
redirect_from: /docs/topic-07/03-basic-nav/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

You can also style `ul`, `ol`, `dl` lists by declaring their elements in the `<style>`, adding color, alignment, etc.

List items (`li`) can also be declared, as showcased a few pages back.

<div id="code-heading">HTML</div>
```html
<head>
  <style>
    ul {background-color: lightgray; text-align: center;}
    li {display: inline; padding: 5px;}
  </style>
</head>

<body>
  <nav>
    <ul>
      <li><a href="./home">Home</a></li>
      <li><a href="./pages/about">About</a></li>
      <li><a href="./pages/contact">Contact</a></li>
    </ul>
  </div>

  <!-- Further page content -->
</body>
```
