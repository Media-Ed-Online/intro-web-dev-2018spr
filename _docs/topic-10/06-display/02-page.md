---
title: Setting Display
module: topic-10
permalink: /docs/topic-10/display-set/
redirect_from: /docs/topic-10/06-display/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The CSS `display:` property allows developers to explicitly specify and/or change these properties for any element. In addition, this property also allows developers to "hide" an element.

This greatly increases the developers ability to create layouts that support the presentation of content in a web browser.

The `display:` property is called on the actual element it is being applied to (as opposed to a parent element holding child elements).


#### Without `display: ` &nbsp;Set
To illustrate, we're going to look at styled navigation lists. Below is the control, with no additional `display: ` property applied:
<br />
<br />

<div class="codepen-embed">
  <style>
    .header-1 {
      width: 400px;
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
    <div class="menu-item-1">
        Home
    </div>
    <div class="menu-item-1">
        Services
    </div>
    <div class="menu-item-1">
        About
    </div>
    <div class="menu-item-1">
        Contact
    </div>
  </header>
</div>
