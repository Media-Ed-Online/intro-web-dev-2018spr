---
title: Properties
module: topic-10
permalink: /docs/topic-10/display-properties/
redirect_from: /docs/topic-10/06-display/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The CSS `display:` property allows developers to explicitly specify and/or change the display properties for any element, including the option to "hide" an element. This greatly increases the developers ability to create layouts that support the presentation of content in a web browser.

The `display:` property is called on the actual element it is being applied to (as opposed to a parent element holding child elements).

The three main display properties that we'll discuss are:
- `block`
- `inline`
- `inline-block`


### Inline

The `display: inline;` rule forces elements to act like inline elements.  Inline elements, unlike block-level elements:

- only take up as much horizontal space as is needed (ignores `width` properties).
- do not force new lines.
- "flow" with content on the screen, and as such, do not respect the margin property.
- cannot change the vertical (top/bottom) distance between themselves and other elements.


### Inline-Block

The `display: inline-block;` rule, like `display: inline;`, removes new lines inherent in block elements. Unlike `display: inline;`, `display: inline-block;` also forces elements to respect margin and vertical spacing properties/rules.

However, this also means these elements will expand horizontally to fill the parent-container. Therefore, you must _explicitly_ set the width of these elements.


### Block
Just like the display property can be used to turn 'block' elements into `inline` or `inline-block` elements, it can also be used to turn 'inline' elements into `block` elements. This technique is often used to create vertical menus out of lists.
