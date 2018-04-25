---
title: Using Weights and Styles
module: topic-09
permalink: /docs/topic-09/using-weight-style/
redirect_from: /docs/topic-09/04-meaning/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<link rel="stylesheet" href="../ex-files/fonts.css">
<link rel="stylesheet" href="../ex-files/style.css">

As your web vocabulary increases, we need to revisit some earlier concepts to update our understanding on their usage.

For many of these values to work, the equivalent font-family for each font weight or style (i.e. "Times-ExtraBold.otf" & "Times-Italic.otf") _must_ be loaded on the client's computer. Otherwise, the browser will round to the nearest font weight or estimate a style comparison.


## Strong vs. Bold

When we wrap words with the `<strong>...</strong>` element, the browser is trying to find a "bold" version of the font. If none exists for the specified font, then they browser _may try_ to bold the selected words on its own (this assumes we have not overwritten the strong elements rules in our CSS).

<div class="codepen-embed">
  <div id="code-heading">RENDER</div>
  <div class="ex-display">
    <h1 class="weight heading-1">I am "normal" weight, using no tags.</h1>
    <h1 class="weight heading-2">My weight is "bold", made with <code>&lt;b&gt;</code> tags.</h1>
    <h1 class="weight heading-3"><strong>I am "strong", made with <code>&lt;strong&gt;</code> tags!</strong></h1>
  </div>
</div>


## Italic vs. Oblique

As with "font weight", the "font style" property will try to find an appropriate, and dedicated, italic font family. If it is unable to do so, it will try to "italicize" the font itself. When a browser slants a font to achieve an italic effect (assuming it was unable to find a truly italic equivalent), this is actually known as an "oblique" style.

In the following example, I have set it up so that each element uses the same font family ("PlayfairDisplay-Regular.ttf"), but I have made it so that the true, "italicized" version ("PlayfairDisplay-Italic.ttf") is not available to the `#heading-2` element.

Notice the difference between the second and third elements. Depending on the browser, the second is either a simple slanted version of the first or the same as the first (again different browsers display things differently).

But the third includes unique serifs (look at the capital 'T's) that are part of the italic version of the font.

<div class="codepen-embed">
  <div id="code-heading">RENDER</div>
  <div class="ex-display">
    <h1 class="style heading-1">I am "normal" style, using “<a href="http://allfont.net/download/playfair-display/" target="_blank">Playfair Display Regular</a>.”</h1>
    <h1 class="style heading-2">I am fake ITALIC, made with <span style="font-style: normal;"><code>&lt;i&gt;</code></span> tags. I am "oblique", if at all...</h1>
    <h1 class="style heading-3">I am a true "ITALIC" style, using “<a href="http://allfont.net/download/playfair-display-italic/" target="_blank">Playfair Display Italic</a>.”
    <br/>AM I NOT BEAUTIFUL?</h1>
  </div>
</div>

Assuming your fonts are loaded correctly, this will not be an issue for you. Specifying an elements style as "italic" should select the correct font-family. If it is not, then you know you need to check your font loading.

<span class="label label-danger">IMPORTANT:</span> At the end of the day, this means you always need to check you site on multiple devices, to ensure it is being displayed as you intend it to be.
