---
title: Adding the &lt;source&gt; Tag
module: topic-06
permalink: /docs/topic-06/video-multi-tag/
redirect_from: /docs/topic-06/09-video/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="33" aria-valuemin="0" aria-valuemax="100" style="width: 33%">
      <span class="sr-only">33% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">

    <span style="color: #999">&lt;video poster="#" width="..." height="..." preload controls &gt;</span><br />

    <span style="margin-left: 30px;"><span style="color: #79AF33; font-weight: bold;"><source</span> <span style="color: #999">src="#" type=""</span> <span style="color: #79AF33; font-weight: bold;">/ ></span></span><br/>

    <span style="color: #999;"></video></span></p>
  </div>
</div>


You can use multiple source elements, which specifies to the browser the video is available in multiple formats. This is the `<source />` element, and again, it is used **instead** of the `src=""` attribute of a `<video>` element.

**NOTE:** Due to a bug on the iPad, you should provide the MP4 video as the first format.
