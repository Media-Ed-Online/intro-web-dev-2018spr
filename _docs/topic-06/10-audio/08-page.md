---
title: The &lt;audio&gt; Element
module: topic-06
permalink: /docs/topic-06/audio-element/
redirect_from: /docs/topic-06/10-audio/08-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div id="code-heading">HTML</div>
```html
<h2>Smooth Sounds for "Puppy" Video</h2>
<audio controls>
    <source src="../media/duckett-audio.wav" />
    <source src="../media/duckett-audio.flac" />
    <source src="../media/duckett-audio.ogg" />
    <source src="../media/duckett-audio.mp3" />
    <p>This browser does not support our audio format.</p>
</audio>
```

<div class="displayed_code_example">
    <h3 style="font-family: open sans;">Smooth Jazz</h3>
    <audio controls preload="auto" width="100%">
      <source src="../media/duckett-audio.ogg" />
      <source src="../media/duckett-audio.mp3" />
        <p>This browser does not support our audio format.</p>
    </audio>
</div>
