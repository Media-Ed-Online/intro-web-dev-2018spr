---
title: Other Attributes
module: topic-06
permalink: /docs/topic-06/video-other-att/
redirect_from: /docs/topic-06/09-video/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><video src="#" poster="#" width="..." height="..."</span> <span style="color: #79AF33; font-weight: bold;">preload controls ></span><span style="color: #999"></video></span></p>
  </div>
</div>

There are several other attributes that can be applied to the `<video>` to make it behave as intended.


### preload

The `preload` attribute takes one of three values and tells the browser how to load the video file if `autoplay` is not present.

- `preload="none"` - tells the browser to do nothing until told to do so by the user.
- `preload="auto"` - tells the browser to download the media file when the page loads.
- `preload="metadata"` - tells the browser to only collect metadata, such as size and length.

### controls
The `controls` attribute is passed alone and does not require a trailing value. This attribute indicates whether the player should display controls. If you do not use this attribute, no controls will be shown by default.

### loop

The `loop` attribute, when present, tells the browser to loop the file.

### autoplay

Like the `controls` attribute, the `autoplay` attribute is included as a single word or not at all. When present, this attribute tells the browser to start playing the file on load.

<span class="label label-info">NOTE:</span> This is considered poor-practice, and in most cases, it is better to let the user choose whether to start the video or not.
