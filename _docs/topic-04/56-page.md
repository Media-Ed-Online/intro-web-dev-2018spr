---
title: Indentation
module: topic-04
permalink: /docs/topic-04/indentation/
redirect_from: /docs/topic-04/56-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There isn't total protocol for indent depth, although standard procedure is to indent one tab (or 2 spaces) for each new element that is a child of the one above it.

Indentation doesn't effect how the page renders, but makes a **huge** difference in the readability of the code.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <body>

    <!-- This is a mess, and considered in poor taste: -->
    <menu id="hot-mess">
            <ul>
    <li><a href="#">Home</a>
      </li><li><a href="/about">About</a></li><li>
                    <a href="/contact">Contact Me</a></li></ul>
    </menu>

    <!-- Rather, this is considered best practice: -->
    <menu id="class-act">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="/about">About</a></li>
        <li><a href="/contact">Contact Me</a></li>
      </ul>
    </menu>

  </body>
</html>
```


Here's an example with nested lists:

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="ZXbPar" data-default-tab="html" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: HTML Lists Pt. 3" class="codepen"></p>
</div>
