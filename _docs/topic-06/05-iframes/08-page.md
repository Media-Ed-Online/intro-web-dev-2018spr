---
title: Media in the &lt;iframe&gt; Element
module: topic-06
permalink: /docs/topic-06/iframes-element-media/
redirect_from: /docs/topic-06/05-iframes/08-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The other common use of the embeddable iframe element is to include media players in your site, such as YouTube, Vimeo, Soundcloud, or Bandcamp.

The process of using these services is similar to that Google map example. From the content you wish to use:

- find the "share" link
- select "embed" as opposed to "share link" tab
- copy the iframe code
- paste it to your site

```html
<!-- Soundcloud Example from UM's own Dr. Michael Musick -->
<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/247762625&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
```

<div class="displayed_code_example">
    <iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/247762625&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>
</div>

<br />


```html
<!-- YouTube Example form UM's own Dr. Michael Musick -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0wEUKJTHnQ" frameborder="0" allowfullscreen></iframe>
```

<div class="displayed_code_example">
    <div class="embed-responsive embed-responsive-16by9"><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/-0wEUKJTHnQ" frameborder="0" allowfullscreen></iframe></div>
</div>
