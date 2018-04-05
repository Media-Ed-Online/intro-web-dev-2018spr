---
title: Property and Value
module: topic-08
permalink: /docs/topic-08/property-value/
redirect_from: /docs/topic-08/01-anatomy/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Inside the declaration, you specify how to style the selected element with property-value pairs.

The pair is separated with a colon (`:`).

Additional declarations are separated with a semicolon (`;`), and are typically placed on new lines.

### Property

The **property** is the aspect about the element that you want to change, i.e. list items or paragraphs.

### Value

The **value** defines how to change a property; for example, color and placement.

<div id="code-heading">CSS</div>
```css
p {
    property1: value;
    property-2: value;
}
```

<span class="label label-info">NOTE:</span> As a rule, there should be no spaces in your property or your value. Each will be a non-breaking set of characters, with multi-word properties created using hyphens (`-`).
