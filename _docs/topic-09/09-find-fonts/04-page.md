---
title: Source
module: topic-09
permalink: /docs/topic-09/font-face-src/
redirect_from: /docs/topic-09/09-find-fonts/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">
      <span class="sr-only">75% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;">
      <span style="color: #999;">@font-face {</span><br/>
        <span style="color: #999;margin-left: 40px;">font-family: '...';</span><br/>
        <span style="color: #79AF33; font-weight: bold; margin-left: 40px;">src: url('#') format('...');</span><br/>
        <span style="color: #999;margin-left: 40px;">font-weight: ;</span><br/>
        <span style="color: #999;margin-left: 40px;">font-style: ;<br/></span>
      <span style="color: #999;">}</span>
    </p>
  </div>
</div>

The source property (`src: url() format()`) tells the browser where to load the font from via the `url()` function, and what type of font it is via the `format()` function.

As with audio and video, not every browser is capable of reading and using every type/format of font. Therefore, you will need to include multiple types of fonts in order to cover support for all browsers.

Common font file-extentions and their formats are:
- `.ttf` - TrueType Fonts, `format('truetype')`
- `.otf` - OpenType Fonts, `format('opentype')`
- `.woff` - Web Open Font Format, `format('woff')`
- `.woff2` -Web Open Font Format 2.0, `format('woff2')`
- `.svg` - SVG Fonts/Shapes, `format('svg')`
- `.eot` - Embedded OpenType Fonts
