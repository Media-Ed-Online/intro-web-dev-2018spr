---
title: The @font-face Selector
module: topic-09
permalink: /docs/topic-09/font-face-selector/
redirect_from: /docs/topic-09/09-find-fonts/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100" style="width: 25%">
      <span class="sr-only">25% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">
      <span style="color: #79AF33; font-weight: bold;">@font-face {</span><br/>
        <span style="color: #999;margin-left: 40px;">font-family: '...';</span><br/>
        <span style="color: #999;margin-left: 40px;">src: url('#') format('...');</span><br/>
        <span style="color: #999;margin-left: 40px;">font-weight: ;</span><br/>
        <span style="color: #999;margin-left: 40px;">font-style: ;<br/></span>
      <span style="color: #79AF33; font-weight: bold;">}</span>
    </p>
  </div>
</div>

To include an external font, you first must tell the browser to load the font and what to refer to it as. To do this, use the `@font-face` rule in your CSS.

This rule is formatted like other CSS selectors, but instead of being used to alter HTML elements, it is used to load in data for CSS to use.
