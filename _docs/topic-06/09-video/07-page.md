---
title: Formats
module: topic-06
permalink: /docs/topic-06/video-formats/
redirect_from: /docs/topic-06/09-video/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

As with many HTML5 elements including the `<video>` and `<audio>` elements, not all browsers support the same format. Therefore, even with HTML5 you need to provide your files in multiple formats.

#### Video
Required self-hosted video formats:

- H264: IE and Safari
- WebM or OGG Video: Android, Chrome, Firefox, Opera

We use the <source /> element inside the `<video>` element to specify the video source. This would be used in-place of the `src=""` attribute in the video element.

You should include a `<p>` element "fallback" that will be displayed if the browser does not support the video element _or_ the format of video used. The browser will display whatever is between the opening and closing video tags.

You can use multiple source elements, which specifies to the browser the video is available in multiple formats.

**NOTE:** Due to a bug on the iPad, you should provide the MP4 video as the first format.
