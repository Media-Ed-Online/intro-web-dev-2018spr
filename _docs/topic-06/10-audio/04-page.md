---
title: Other Attributes
module: topic-06
permalink: /docs/topic-06/audio-other-att/
redirect_from: /docs/topic-06/10-audio/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

#### controls

When the `controls` attribute is supplied it indicates the browser should supply its own controls for playback. If you do not use this attribute, no controls will be shown by default.

#### autoplay

When used, this attribute specifies that the file should play automatically.

**NOTE:** Remember, this is considered poor-practice, and in most cases, it is better to let the user choose whether to start the audio or not.

#### preload

As with the `<video>` element, this attribute tells the browser what to do when the page loads. It can have one of three values:

- `none` - The browser should not load the audio until the user presses play.
- `auto` (default) - The browser should download the audio when the page loads.
- `metadata` - The browser should just collect information such as the size, first frame, track list, and duration.

#### loop

This tells the browser whether or not to loop the audio.
