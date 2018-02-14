---
title: Linking Internally in the Site
module: topic-04
permalink: /docs/topic-04/intro-int-links/
redirect_from: /docs/topic-04/48-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/homepage.svg" alt="Tim Berners-Lee" style="width: 100px; margin-top: 0;" />

_Remember?_ **Relative URLs** contain no protocols or domain information. This is convenient because they are shorter, but can _only_ reference files in the same path.

It also should be noted that in the language of web design, the `index.html` file is referred to as the **home page** once hosted, as it becomes the "entry" to your site. It is also the page most users will return to again and again as your "base of opperations," as it were.

<div id="code-heading">HTML</div>
```html
<a href="../index.html" target="_blank">Back to Home</a>
```
