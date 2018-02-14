---
title: Adding Attributes
module: topic-04
permalink: /docs/topic-04/attributes/
redirect_from: /docs/topic-04/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Attributes are always placed inside the opening tag for the element they refer to. Attributes are always provided in a **key=“value”** pair. The **key** is an identifier the the browser processor will recognize. These keys are defined by the W3 Consortium that defined HTML5 specification. The **value** provides information about the attribute.

The value is always surrounded by double quotations. One reason for this is that it allows for spaces to be used within the value for an attribute. Furthermore, the attribute will have one space placed between the tag label and the attribute, as well as between any subsequent attributes.

<div id="code-heading">HTML</div>
```html
<p align="left">This is a paragraph element, made with "<p>" tags.<br/>
It will align to the left of its container.</p>
```
