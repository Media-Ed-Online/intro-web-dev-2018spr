---
title: Setting Bold and Italic
module: topic-09
permalink: /docs/topic-09/bold-italic/
redirect_from: /docs/topic-09/04-meaning/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<link rel="stylesheet" href="../ex-files/fonts.css">
<link rel="stylesheet" href="../ex-files/style.css">

Before we look at how to include external fonts, let's discuss font weight and font style. These are used to determine if a font is **bold** and/or _italic_.

<div class="codepen-embed">
  <div id="code-heading">RENDER</div>
  <div class="ex-display">
    <h1 class="weight heading-1">I am "normal" text, made without any CSS properties.</h1>
    <h1 class="weight heading-2">I am "bold" text, made with the <span style="font-weight: normal;"><code>font-weight</code></span> property.</h1>
    <h1 class="style heading-2" style="font-family: sans-serif;">I am "italic" text, made with the <span style="font-style: normal;"><code>font-style</code></span> property.</h1>
  </div>
</div>

<span class="label label-danger">IMPORTANT:</span> Please note that I explicitly stated these appearances are a result of CSS properties, _not_ HTML tags.

<div id="code-heading">CSS</div>
```css
#line-one {
  /* No rules. */
}
#line-two {
  font-weight: bold;
}
#line-three {
  font-style: italic;
}
```

Using these rules in your CSS can eliminate the need for tags in your HTML, saving time and effort.
