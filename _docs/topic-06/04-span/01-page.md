---
title: The &lt;span&gt; Element
module: topic-06
permalink: /docs/topic-06/span-element/
redirect_from: /docs/topic-06/04-span/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The **span element** is the inline equivalent of the `<div>` element.

<div class="container-row">
  <img src="../img/legos-spans.png" alt="stacked building blocks with stickers representing span elements" title="Blocks can have multiple spans!" style="float: right; width: 150px; margin-top: 0;" />

  <p>This means that spans can exist within divs, and do not create blocks. It serves to identify or group content together that requires organization or extra styling. You can have multiple span elements inside a div.</p>

  <p>One specific use for the <code>&lt;span&gt;</code> element is to identify text that needs to appear visually unique on the rendered HTML page.</p>

  <p>As with the <code>&lt;div&gt;</code> element, the <code>&lt;span&gt;</code> element should include a class or ID attribute to provide:</p>

  <ul>
    <li>a reference to styling code</li>
    <li>and/or information to developers about the inner content</li>
  </ul>
</div>

<div id="code-heading">HTML</div>
```html
<div id="long-blue" class="long-block">
  <p>A block with a <span class="circle">circle</span> and <span class="triangle">triangle</span> on it.</p>
</div>

<div id="long-red" class="long-block">
  <p>A block with a <span class="circle">circle</span> on it.</p>
</div>
```
