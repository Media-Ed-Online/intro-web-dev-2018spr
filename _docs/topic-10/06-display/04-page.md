---
title: Inline-Block
module: topic-10
permalink: /docs/topic-10/display-inline-block/
redirect_from: /docs/topic-10/06-display/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The `display: inline-block;` rule, like `display: inline;`, removes 'new line's inherent in block elements. Unlink `display: inline;`, `display: inline-block;` also forces elements to respect margin, and vertical spacing properties/rules.

However, this also means these elements will expand, horizontally to fill the parent-container. Therefore, you must explicitly set the width of these elements.


<div class="codepen-embed">
  <style>
    .header-1 {
      width: 500px;
      margin: auto;
      background-color: #d0d0d0;
      font-family: sans-serif;
      font-size: 14pt;
      text-align: center;
      text-transform: uppercase;
      margin-bottom: 10px;
      padding: 0.5em;
    }
    .menu-item-1 {
      margin: auto;
      padding: 0.5em;
      min-width: 100px;
      color: #fff;
      background-color: goldenrod;
    }
    .menu-item-1:hover {
      background-color: gold;
      color: #333;
    }
    .display-inline-1 {
      display: inline;
    }
    .display-inline-block-1 {
      display: inline-block;
    }
  </style>
  <header class="header-1">
    <div class="menu-item-1 display-inline-block-1">
      Home
    </div>
    <div class="menu-item-1 display-inline-block-1">
      Services
    </div>
    <div class="menu-item-1 display-inline-block-1">
      About
    </div>
    <div class="menu-item-1 display-inline-block-1">
      Contact
    </div>
  </header>
</div>
