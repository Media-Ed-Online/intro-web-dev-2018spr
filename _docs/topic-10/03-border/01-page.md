---
title: Drawing Edges
module: topic-10
permalink: /docs/topic-10/border-intro/
redirect_from: /docs/topic-10/03-border/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/box-model-border.gif" alt="borders being drawn" style="width: 350px; margin: 0 auto 30px;" />

The first thing we'll look at in the box model are **borders.** You are already familiar with borders through your past assignments, but there's a lot we haven't explored yet.

You can create a border in one lump property (known as the "shorthand"), or each side and property individually.

### Border Shorthand Property

For borders, the property to define the entire border is simply `border: `. As its declaration, it expects three values, in order: width, style, color.

<div id="code-heading">CSS</div>

```css
div {
    border: 2px solid #623529;
}
```

### Individual Border Properties

You may also define each side of a box individually for each partial border property or for the single border property. Simply add the side in question:

<div id="code-heading">CSS</div>

```css
div {
    border: ;
    border-top: ;
    border-right: ;
    border-bottom: ;
    border-left: ;

    border-width: ;
    border-top-width: ;
    border-right-width: ;
    border-bottom-width: ;
    border-left-width: ;

    border-style: ;
    border-top-style: ;
    border-right-style: ;
    border-bottom-style: ;
    border-left-style: ;

    border-color: ;
    border-top-color: ;
    border-right-color: ;
    border-bottom-color: ;
    border-left-color: ;
}
```

<span class="label label-info">NOTE:</span> A number of CSS properties that take multiple property declarations to define also offer the option of defining the entire thing with a single property.
