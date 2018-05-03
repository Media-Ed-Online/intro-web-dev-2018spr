---
title: Rules
module: topic-10
permalink: /docs/topic-10/border-rules/
redirect_from: /docs/topic-10/05-border/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

### Border Shortcut Property

A number of CSS properties that take multiple property declarations to define also offer the option of defining the entire thing with a single property. In this case, the property to define the entire border, is simply `border: `. As its declaration, it expects three values, in order: width, style, color.

<div id="code-heading">CSS</div>

```css
div {
    border: 2px solid #623529;
}
```

### Individual Border Properties

As with padding and margin, you may also define each side of a box individually for each partial border property or for the single border property. Simply add the side in question:

<div id="code-heading">CSS</div>

```css
div {
    border: ;
    border-top: ;
    border-bottom: ;
    border-left: ;
    border-right: ;

    border-width: ;
    border-top-width: ;
    border-bottom-width: ;
    border-left-width: ;
    border-right-width: ;

    border-style: ;
    border-top-style: ;
    border-bottom-style: ;
    border-left-style: ;
    border-right-style: ;

    border-color: ;
    border-top-color: ;
    border-bottom-color: ;
    border-left-color: ;
    border-right-color: ;
}
```

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="OOWEKB" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Boarders, Pt. 3" class="codepen"></p>
</div>
