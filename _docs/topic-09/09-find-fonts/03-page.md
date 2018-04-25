---
title: Family
module: topic-09
permalink: /docs/topic-09/font-face-family/
redirect_from: /docs/topic-09/09-find-fonts/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%">
      <span class="sr-only">50% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">
      <span style="color: #999;">@font-face {</span><br/>
        <span style="color: #79AF33; font-weight: bold; margin-left: 40px;">font-family: '...';</span><br/>
        <span style="color: #999;margin-left: 40px;">src: url('#') format('...');</span><br/>
        <span style="color: #999;margin-left: 40px;">font-weight: ;</span><br/>
        <span style="color: #999;margin-left: 40px;">font-style: ;<br/></span>
      <span style="color: #999;">}</span>
    </p>
  </div>
</div>

Like mentioned previously, `font-family: ` can be used for generic font classes (<span style="font-family: serif; font-size: 1.2em;">serif</span>, <span style="font-family: sans-serif; font-size: 1.2em;">sans-serif</span>, and <span style="font-family: monospace; font-size: 1.2em;">monospace</span>) and also for specific font family names.

Using `@font-face`, fonts can be named in relation to their files. This can be the same for the whole family (i.e. `font-family: 'Playfair Display'`) or specific to different variations (i.e. `font-family: 'Playfair Display Bold'`) depending on how the rule is structured.
