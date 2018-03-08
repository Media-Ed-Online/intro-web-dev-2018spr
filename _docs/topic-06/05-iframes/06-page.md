---
title: Sites in the &lt;iframe&gt; Element
module: topic-06
permalink: /docs/topic-06/iframes-element-sites/
redirect_from: /docs/topic-06/05-iframes/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Let's see how our own site looks in an iframe. You should see the "mobile version," or a compressed view optimized for smaller portals.

<span class="label label-info">NOTE:</span> This is not an empty element. You should include a closing tag when using the iframe element. Otherwise, unexpected results may occur.

<div id="code-heading">HTML</div>
```html
<iframe src="https://media-ed-online.github.io/intro-web-dev/" width="600px" height="500px"></iframe>
```

<div class="codepen-embed">
  <iframe src="https://media-ed-online.github.io/intro-web-dev/" width="100%" height="500px"></iframe>
</div>


### How-To:

To embed an external site to your page, simply build the `<iframe>` element, and include the site's absolute URL.

<span class="label label-info">NOTE:</span> For a variety of reasons, not all sites will work in an iframe. Including a hyperlink to the site below the iframe is a good idea.
