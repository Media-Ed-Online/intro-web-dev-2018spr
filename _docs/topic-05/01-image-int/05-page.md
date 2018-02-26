---
title: Title
module: topic-05
permalink: /docs/topic-05/img-title/
redirect_from: /docs/topic-05/01-image-int/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

As with the alt text attribute, you should also get in the habit of always including a **title attribute**, which is `title=""`. Most browsers will display this text as a tooltip when a user hovers their mouse over am image with the included attribute.


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
      <span class="sr-only">60% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><img src="#" alt="..."</span> <span style="color: #79AF33; font-weight: bold;">title="..."</span> <span style="color: #999">width="..." height="..." /></span></p>
  </div>
</div>


<span class="label label-danger">IMPORTANT:</span> The alt and/or title attributes will also be used by some browsers in the case where the image itself cannot load.
