---
title: Multiple Sources
module: topic-06
permalink: /docs/topic-06/audio-multi-src/
redirect_from: /docs/topic-06/10-audio/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="66" aria-valuemin="0" aria-valuemax="100" style="width: 66%">
      <span class="sr-only">66% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">

    <span style="color: #999">&lt;audio preload controls &gt;</span><br />

    <span style="margin-left: 30px;"><span style="color: #999"><source</span> <span style="color: #79AF33; font-weight: bold;">src="#"</span> <span style="color: #999">type="" / ></span></span><br/>

    <span style="color: #999;"></audio></span></p>
  </div>
</div>


When using more than just `.mp3` you should include multiple versions of the file, with decreasing preference. This allows the browser to then use the file format that it supports.

This can be done by omitting the `src=""` attribute from the `<audio>` element and instead using a separate `<source />` element inside the parent `<audio>` element.

The `<source />` element is an empty element, and accepts the `src=""` attribute to provide the URL to the browser.
