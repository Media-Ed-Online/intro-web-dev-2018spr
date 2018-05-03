---
title: Inline
module: topic-10
permalink: /docs/topic-10/display-inline/
redirect_from: /docs/topic-10/06-display/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The `display: inline;` rule forces elements to act like inline elements, similar to how the `<span>` elements acted above. Inline elements, unlike block-level elements:

- only take up as much horizontal space as is needed (ignores `width` properties).
- do not force new lines.
- "flow" with content on the screen, and as such, do not respect the margin property.
- cannot change the vertical (top/bottom) distance between themselves and other elements.

**NOTE:** Since inline elements "flow" it is also important to recognize that their content can "flow" onto the next line...


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
    <div class="menu-item-1 display-inline-1">
      Home
    </div>
    <div class="menu-item-1 display-inline-1">
      Services
    </div>
    <div class="menu-item-1 display-inline-1">
      About
    </div>
    <div class="menu-item-1 display-inline-1">
      Contact
    </div>
  </header>
</div>
