---
title: Ordering
module: topic-04
permalink: /docs/topic-04/ordering/
redirect_from: /docs/topic-04/54-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Most languages read and process top-to-bottom, so its important to list these elements linearly and/or logically down the page.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>

<html>
  <body>
  
    <!-- This is improper ordering of blocks! -->
    <!-- The footer should come after the main content. -->
    <footer>
      <p>(C) Justine Evans, 2018</p>
    </footer>

    <main>
      <h1>"Debt"</h1>
      <h2>A sonnet about student loans.</h2>
    </main>

  </body>
</html>
```
