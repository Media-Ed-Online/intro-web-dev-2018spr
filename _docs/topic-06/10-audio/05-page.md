---
title: Formats
module: topic-06
permalink: /docs/topic-06/audio-formats/
redirect_from: /docs/topic-06/10-audio/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

### Browser Support and the Source Tag

Notice that the `<audio>` element is not an "empty element" and requires both an opening and closing tag. This serves a number of purposes, but the most important is that the developer can include content between the tags that will be displayed or called in the case that an end-user's browser does not support the `<audio>` element or audio file format.

You should always include extra markup inside the tags for this potential case.

<div id="code-heading">HTML</div>
```html
<audio src="">
    <p>This browser does not support our audio format.</p>
</audio>
```

#### Audio
Best included self-hosted audio formats:

- .mp3: Good quality for file size, but proprietary.
- .ogg: Open-sourced.
- .wav<a href="#lossless-formats">*</a>: Lossless, but larger files.

There are many file formats that audio files can be rendered to. The most popular and well known is likely `.mp3`.

This is because the compression achieved creates smaller file sizes without comprising audio quality too greatly. However, `.mp3` is technically a proprietary format, and as such, some people are hesitant to use it.

If you find yourself working for an audio-based client, they may also have strong opinions about what file types they want prioritized. For example, they may want to use `.ogg` as this is an open-source based audio format.

<p id="lossless-formats">Your clients may also insist that you include lossless or uncompressed audio file formats such as <code>.wav</code>, <code>.aiff</code>, or <code>.flac</code>.</p>
