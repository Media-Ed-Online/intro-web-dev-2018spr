---
title: Types
module: topic-06
permalink: /docs/topic-06/video-multi-type/
redirect_from: /docs/topic-06/09-video/10-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Use the `type=""` attribute to tell the browser what format the video is in. (i.e. video/H264, video/mp4) Otherwise, it will download some of the video to see if it can play the file, find that it cannot, and then try the next one until it has exhausted all options or found a valid file format. (**This takes time and bandwidth!**)

The codec that was used to encode the video is supplied within the type attribute, following the video file type, separated by a semicolon (`;`). For example, `type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"'`.

**NOTE:** The use of double and single quotes to delineate.
