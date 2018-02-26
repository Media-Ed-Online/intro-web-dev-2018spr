---
title: Width and Height
module: topic-05
permalink: /docs/topic-05/img-size/
redirect_from: /docs/topic-05/01-image-int/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><img src="#" alt="..." title="..."</span> <span style="color: #79AF33; font-weight: bold;">width="..." height="..."</span> <span style="color: #999">/></span></p>
  </div>
</div>



Another set of attributes you should add every time is `width=""` & `height=""`. The values passed to these attributes are a string with an integer, representing the **width and height** that the image is to be displayed at.

In most situations, _the width and height of the image file should be the same width and height that you enter as attributes_ and want used in your web page. In the case that these differ, these attributes will scale the image file to the specified size passed to the attributes.

Another reason for including these attributes is that the web browser uses these to reserve the correct amount of space for the image on the page when rendering, even in the case where the page is rendered before the image file is delivered to the browser. This means that the page will not have to ‘re-render’ to accommodate an image that loads after the rest of the page.
