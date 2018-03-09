---
title: Types
module: topic-06
permalink: /docs/topic-06/video-multi-type/
redirect_from: /docs/topic-06/09-video/10-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">

    <span style="color: #999">&lt;video poster="#" width="..." height="..." preload controls &gt;</span><br />

    <span style="margin-left: 30px;"><span style="color: #999"><source src="#"</span> <span style="color: #79AF33; font-weight: bold;">type=""</span> <span style="color: #999">/ ></span></span><br/>

    <span style="color: #999;"></video></span></p>
  </div>
</div>


Use the `type=""` attribute to tell the browser what format the video is in. (i.e. video/H264, video/mp4) Otherwise, it will download some of the video to see if it can play the file, find that it cannot, and then try the next one until it has exhausted all options or found a valid file format. (**This takes time and bandwidth!**)

The codec that was used to encode the video is supplied within the type attribute, following the video file type, separated by a semicolon (`;`). For example, `type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"'`.

<span class="label label-info">NOTE:</span> The use of double and single quotes to delineate.
