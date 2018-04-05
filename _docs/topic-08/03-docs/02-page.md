---
title: The &lt;link&gt; Tag
module: topic-08
permalink: /docs/topic-08/link-tag/
redirect_from: /docs/topic-08/03-docs/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100" style="width: 25%">
      <span class="sr-only">25% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #79AF33; font-weight: bold;"><link</span> <span style="color: #999">rel="stylesheet" type="text/css" href="#"</span> <span style="color: #79AF33; font-weight: bold;">/ ></span></p>
  </div>
</div>

It is necessary to tell the browser to use the style defined within the document. To do this, you will add the "link element" (`<link />`) inside the document's head element. Just like the style element, the link element is typically placed near or at the end of the head element. The link element is an empty element, so it only requires a single tag.

<span class="label label-info">NOTE:</span> You may link more than one CSS document by simply including multiple link elements. This is common for larger sites.
