---
title: Formats and Browser Support
module: topic-06
permalink: /docs/topic-06/video-formats/
redirect_from: /docs/topic-06/09-video/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

As with many HTML5 elements including the `<video>` and `<audio>` elements, not all browsers support the same format. Therefore, even with HTML5 you need to provide your files in multiple formats.

### Video Formats
Required self-hosted video formats:

- H264: IE and Safari
- WebM or OGG Video: Android, Chrome, Firefox, Opera

We use the <source /> element inside the `<video>` element to specify the video source. **This would be used in-place of the `src=""` attribute in the video element.**


### Not Supported!

You should include a `<p>` element "fallback" that will be displayed if the browser does not support the video element _or_ the format of video used. The browser will display whatever is between the opening and closing video tags.

<span class="label label-info">NOTE:</span> Any written content placed between the `<video>` will display should the video not load in the browser. You should always include some descriptive text of the video (like with images), so users know what element they are missing.

<div id="code-heading">HTML</div>
```html
<video src="#" poster="#" width="..." height="..." preload controls>
  <p>A video of a puppy playing in the snow.</p>
  <p>Sorry, your browser doesn't support embedded videos, but don't worry, you can <a href="./media/videofile.webm">download it</a> and watch it with your favorite video player!</p>
</video>
```
