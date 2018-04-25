---
title: The @font-face Rule
module: topic-09
permalink: /docs/topic-09/font-face-rule/
redirect_from: /docs/topic-09/09-find-fonts/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<link href="https://fonts.googleapis.com/css?family=Playfair+Display:400,400i,700,700i,900,900i" rel="stylesheet">

In the following example, 6 types of the font-family <span style="font-family:'Playfair Display'; font-size: 1.2em;">“[Playfair Display](https://fonts.google.com/specimen/Playfair+Display)”</span> are imported.

There are three weights of this font:

<div style="font-family: 'Playfair Display', serif; font-size: 1.25em;">
  <ul>
    <li>regular (400 and <i>400 italic</i>)</li>
    <li><span style="font-weight: 700">bold (700 and <span style="font-style: italic">700 italic</span>)</span></li>
    <li><span style="font-weight: 900">bold (900 and <span style="font-style: italic">900 italic</span>)</span></li>
  </ul>
</div>

When selecting the font for use, the CSS specifies the `font-weight:` and `font-style:` which then allows the browser to call the correct font package.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="RjNygz" data-default-tab="css" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] External Fonts, Pt. 2 (FONTS.css)" class="codepen"></p>
  <p data-height="600" data-theme-id="30567" data-slug-hash="QOwrQd" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] External Fonts, Pt. 2 (STYLE.css)" class="codepen"></p>
</div>

<!--Please continue to the next pages to see how this Pen was created and set-up in the directory.-->
