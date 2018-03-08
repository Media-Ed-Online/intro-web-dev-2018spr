---
title: Maps in the &lt;iframe&gt; Element
module: topic-06
permalink: /docs/topic-06/iframes-element-maps/
redirect_from: /docs/topic-06/05-iframes/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

In addition to displaying other webpages in the main webpage, the iframe element is often used to display two specific types of instances. The first of these is to include Google maps.

<div id="code-heading">HTML</div>
```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2728.0484933883513!2d-113.9858143984305!3d46.86241807904005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x535dcc33c3d4cbd5%3A0xd77cd4f46bdf5b89!2sMcGill+Hall%2C+32+Campus+Dr%2C+Missoula%2C+MT+59812!5e0!3m2!1sen!2sus!4v1488574173329" width="600" height="450" frameborder="0" allowfullscreen></iframe>
```

<div class="codepen-embed">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2728.0484933883513!2d-113.9858143984305!3d46.86241807904005!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x535dcc33c3d4cbd5%3A0xd77cd4f46bdf5b89!2sMcGill+Hall%2C+32+Campus+Dr%2C+Missoula%2C+MT+59812!5e0!3m2!1sen!2sus!4v1488574173329" width="100%" height="300" frameborder="0" allowfullscreen></iframe>
</div>


### How-To:

From the Google maps page, after completing a search, you can click the "share" button. This opens a separate pop-up, where you should select the "Embed map" option. You can then tweak the display options, and copy Google's iframe code to include on your site.

![Image showing the "embed map" option from google maps.](../img/google-maps-embed.png)

Including this code on your site will create an embedded google map that your visiting users may interact with. Typically, this is useful in showing where a business location is.
