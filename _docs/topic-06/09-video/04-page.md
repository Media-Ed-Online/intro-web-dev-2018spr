---
title: Poster
module: topic-06
permalink: /docs/topic-06/video-poster/
redirect_from: /docs/topic-06/09-video/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
      <span class="sr-only">60% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video src="#"</span> <span style="color: #79AF33; font-weight: bold;">poster="#"</span> <span style="color: #999">width="..." height="..." preload controls ></video></span></p>
  </div>
</div>

The `poster=""` attribute should always be supplied with the `<video>` element. This attribute takes a URL as its value, which should point to an image that is displayed in place of the video until the visitor elects play the video.

**NOTE:** The image should be the same width/height ratio as the video element.
![Image of matching video and video poster sizes](../img/video-poster-sizing.png)
