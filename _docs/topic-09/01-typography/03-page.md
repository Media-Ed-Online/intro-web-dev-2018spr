---
title: Font Categories
module: topic-09
permalink: /docs/topic-09/font-categories/
redirect_from: /docs/topic-09/01-typography/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Licensing has a lot to do with how you'll select your fonts. In no way is every font available to every user - in fact, we're actually quite limited on what fonts platforms share:

<img src="../img/web-safe-font-venn.png" style=" margin: 20px auto; width: 400px;" alt="venn diagram of web-safe fonts for Windows 7 and MacOS X" title="Window 7 vs MacOS X Available Fonts"/>

In other words, "Calabri" will appear for Windows users accessing the site, but perhaps not for Mac users. The browser will then request a fallback or default font to render for those users, which may or may not look as the dev intended.

<div class="codepen-embed">
  <ul class="nav nav-tabs">
    <li class="active"><a href="#system" data-toggle="tab">System Fonts</a></li>
    <li><a href="#web" data-toggle="tab">Web Fonts</a></li>
    <li><a href="#safe" data-toggle="tab">Web-Safe Fonts</a></li>
  </ul>

  <div id="myTabContent" class="tab-content">
    <div class="tab-pane fade active in" id="system">
      <p>System fonts are those already installed on your local device and system. These are available to you and most programs you use, but are not necessarily to the web (usually due to licensing).</p>
      <p>You may have never second-guessed your use of system fonts, because you often select them with the intent to print. But most system fonts are not set up for the web, and should be limited to usage in logos and other branding. This is because they must be exported as <em>images</em>, affecting both assistive technologies and search engine indexing.</p>
      <div style="width: 100%; max-width: 400px; margin: 40px auto;">
        <img src="../img/system-font-ex-bakery.svg" style="margin: auto;" />
        <p style="margin-top: 10px;">Font: “<a href="http://www.stereo-type.fr/fonts/bakery/" target="_blank">Bakery</a>”</p>
      </div>
      <div style="width: 100%; max-width: 400px; margin: 40px auto;">
        <img src="../img/system-font-ex-marker.svg" style="margin: auto;" />
        <p style="margin-top: 10px;">Fonts: “<a href="https://fonts2u.com/fresh-marker.font" target="_blank">Fresh Marker</a>” and “<a href="https://www.whatfontis.com/Armageda-Wide.font" target="_blank">Armegeda Wide</a>”</p>
      </div>
      <div style="width: 100%; max-width: 400px; margin: 40px auto;">
        <img src="../img/system-font-ex-maybe.svg" style="margin: auto;" />
        <p style="margin-top: 10px;">Font: “<a href="http://fontpro.com/maybe-maybe-not-font-429" target="_blank">Maybe Maybe Not</a>”</p>
      </div>
      <p><span class="label label-info">NOTE:</span> If you try to select one the fake brand names above, you'll see that your cursor grabs an image, and cannot highlight text (because there is none to do so). This is why text-images should be used sparingly.</p>
    </div>

    <div class="tab-pane fade" id="web">
      <p>Web fonts are custom fonts hosted on a server. They do not have to be available on the user's device to appear, but require certain elements to get called up correctly.</p>
      <p>65% of websites currently use web fonts. These fonts are optimized for performing on the web, but are not full-proof. You should take into consideration browser compatibility, rendering speeds, and availability when selecting these fonts.</p>
      <p>This site uses the web fonts:</p>
        <ul>
          <li><span style="font-family: 'Ubuntu,' sans-serif; font-size:1.25em;"><a href="https://design.ubuntu.com/font/" target="_blank">Ubuntu</a></span></li>
          <li><span style="font-family: Menlo, monospace; font-size:1.25em;"><a href="https://en.wikipedia.org/wiki/Menlo_(typeface)" target="_blank">Menlo</a></span> (with fallbacks)</li>
        </ul>
      <p>Common repositories for utilizing fonts in this way are <a href="https://fonts.google.com/" target="_blank">Google Fonts</a>, <a href="https://www.fontsquirrel.com/" target="_blank">Font Squirrel</a>, and <a href="https://typekit.com/" target="_blank">Adobe Typekit</a>.</p>
    </div>

    <div class="tab-pane fade" id="safe">
    <p>Fonts that developers can count on being available by the system are known as "web-safe" fonts. These include font families that both Windows and Mac should have (see the graphic above).</p>

    <p>Web-safe fonts include:</p>
      <ul>
        <li style="font-family: Arial; font-size:1.25em;">Arial</li>
        <li style="font-family: Georgia; font-size:1.25em;">Georgia</li>
        <li style="font-family: Times; font-size:1.25em;">Times New Roman</li>
        <li>...as well as these other <a href="http://www.ampsoft.net/webdesign-l/WindowsMacFonts.html" target="_blank">web safe fonts</a></li>
      </ul>

      <p>The advantage of using fonts from this list is that the client computer will already have the font. This reduces load times and may increase performance.</p>
    </div>

  </div>
