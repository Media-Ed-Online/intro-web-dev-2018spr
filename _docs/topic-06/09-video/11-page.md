---
title: The &lt;video&gt; Element
module: topic-06
permalink: /docs/topic-06/video-element/
redirect_from: /docs/topic-06/09-video/11-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div id="code-heading">HTML</div>
```html
<video poster="../imgs/duckett-puppy-poster.png" width="768" height="576" preload controls loop>
	<source src="media/ducket-puppy.mp4" type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"' />
	<source src="media/duckett-puppy.webm" type='video/webm;codecs="vp8, vorbis"' />
	<p>A video of a puppy playing in the snow.</p>
</video>
```

<div class="displayed_code_example">
<center>
<video poster="../imgs/duckett-puppy-poster.png" width="400" height="320" preload controls loop>
	<source src="../media/duckett-puppy.mp4" type='video/mp4;codecs="avc1.42E01E, mp4a.40.2"' />
	<source src="../media/duckett-puppy.webm" type='video/webm;codecs="vp8, vorbis"' />
	<p>A video of a puppy playing in the snow.</p>
</video>
</center>
</div>
