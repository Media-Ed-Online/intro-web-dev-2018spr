---
title: Href
module: topic-08
permalink: /docs/topic-08/link-href/
redirect_from: /docs/topic-08/03-docs/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><link rel="stylesheet" type="text/css"</span> <span style="color: #79AF33; font-weight: bold;">href="#"</span> <span style="color: #999">/ ></span></p>
  </div>
</div>

Provide the relative or absolute URL as the value to the `href=""` attribute. This tells the browser where the document is located at.

The process of linking CSS documents is the same as you've been doing for other site files, such as images and videos.


### External Style Sheets
Many sites link out to external CSS documents as well, and will be linked via an _absolute URL_.

<div id="code-heading">HTML</div>
```html
<head>
  <title>Tuna the Cat</title>
  <link rel="stylesheet" type="text/css" href="https://codepen.io/rachelnabors/pen/bpAJH.css">
</head>
```


### Internal Style Sheets
Internal files, like your own created CSS document, should be linked via _relative URL_.

<div id="code-heading">HTML</div>
```html
<head>
  <title>Tuna the Cat</title>
  <link rel="stylesheet" type="text/css" href="./css/style.css">
</head>
```

<span class="label label-info">NOTE:</span> When linking the same stylesheet in your child pages, you would need to add an additional 'dot' to your file path (`../`) to move up a directory.
