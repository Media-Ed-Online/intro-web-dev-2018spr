---
title: Styling
module: topic-06
permalink: /docs/topic-06/class-style/
redirect_from: /docs/topic-06/02-class-att/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The class attribute follows the same technical naming conventions as the ID attribute. As with the ID attribute, the class attribute value should be as descriptive as possible about the function or element types groups, while prioritizing both brevity and readability.

Unlike the ID attribute which should contain a single unique ID value, elements may have more than one class assignment. In this case, a space separates each class.

<span class="label label-info">NOTE:</span> This means that while every element should have a unique id, several elements can reference the _same_ class.

<div id="code-heading">HTML</div>
```html
<div id="example-1" class="class-name-1 class-name-2 notice-the-space">
    <p>Notice the space between each of the three class names.</p>
</div>

<div id="example-2" class="class-name-2">
    <p>This paragraph has a unique id, but the same "class-name-2" as the one above it.</p>
</div>
```
