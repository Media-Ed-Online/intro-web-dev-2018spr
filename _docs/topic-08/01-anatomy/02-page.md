---
title: Elements and Rules
module: topic-08
permalink: /docs/topic-08/multi-selectors/
redirect_from: /docs/topic-08/01-anatomy/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

**Rules** can be applied singularly or en masse to one or more selectors:

<span class="label label-info">NOTE:</span> CSS is not whitespace dependent. In other words, you do not need to include extra lines between rules. However, this shown style increases readability of your code. _It's polite._


### Multiple Selectors with Different Rules

When applying different rules to elements, you simply need to write another selector/declaration set. The closing **curly bracket** (`}`) tells the browser the rule is finished.

<div id="code-heading">CSS</div>
```css
/* Rule 1: Applied to all h1 elements. */
h1 {
    /* Style declarations go here. */
}

/* Rule 2: Applied to all paragraphs. */
p {
    /* Style declarations go here. */
}
```


### Multiple Selectors with the Same Rules

If you need to apply the same rules to more than one element, you can select multiple elements in a single style rule. To do so, separate each selector element with a comma (`,`).

You can then still go on to apply additional, unique style rules to an already styled element. These rules will simply be cumulative.

<div id="code-heading">CSS</div>
```css
h1, h2, p {
    /* Style rules applied to all h1, h2, and paragraph elements. */
}

p {
    /* Additional style rules applied only to paragraph elements. */
}
```
