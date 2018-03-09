---
title: Other Attributes
module: topic-06
permalink: /docs/topic-06/audio-other-att/
redirect_from: /docs/topic-06/10-audio/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%">
      <span class="sr-only">100% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><audio src="#"</span> <span style="color: #79AF33; font-weight: bold;">preload controls ></span><span style="color: #999"></audio></span></p>
  </div>
</div>


There are several other attributes that can be applied to the `<audio>` to make it behave as intended.

### controls

When the `controls` attribute is supplied it indicates the browser should supply its own controls for playback. If you do not use this attribute, no controls will be shown by default.

### autoplay

When used, this attribute specifies that the file should play automatically.

<span class="label label-info">NOTE:</span> Remember, this is considered poor-practice, and in most cases, it is better to let the user choose whether to start the audio or not.

### preload

As with the `<video>` element, this attribute tells the browser what to do when the page loads. It can have one of three values:

- `none` - The browser should not load the audio until the user presses play.
- `auto` (default) - The browser should download the audio when the page loads.
- `metadata` - The browser should just collect information such as the size, first frame, track list, and duration.

### loop

This tells the browser whether or not to loop the audio.
