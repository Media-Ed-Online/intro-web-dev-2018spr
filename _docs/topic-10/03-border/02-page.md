---
title: Properties
module: topic-10
permalink: /docs/topic-10/border-properties/
redirect_from: /docs/topic-10/03-border/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Like margin and padding (which you'll learn about soon), borders help define the amount of space a box or element takes up, as well as its relationship to other boxes.

_Unlike_ margin and padding, however, the border portion of the box can be separately colored, and has multiple style options. Border is more of a visual styling tool, than a space management tool.

There are three properties that make up border:
- Width
- Style
- Color


### Border Width

The first property that defines a boxes border is the "**border width**" (`border-width: `). This takes a measurement value that may be pixels, points, percentages, or ems.


### Border Style

The second property that defines a boxes border is the "**border style**" (`border-style: `). This takes a predefined keyword as its property:

- <div style="border-style:solid;padding:0.25em;margin-bottom:0.5em;">solid</div>
- <div style="border-style:dashed;padding:0.25em;margin-bottom:0.5em;">dashed</div>
- <div style="border-style:dotted;padding:0.25em;margin-bottom:0.5em;">dotted</div>
- <div style="border-style:double;padding:0.25em;margin-bottom:0.5em;">double</div>
- <div style="border-style:inset;padding:0.25em;margin-bottom:0.5em;">inset</div>
- <div style="border-style:outset;padding:0.25em;margin-bottom:0.5em;">outset</div>
- <div style="border-style:groove;padding:0.25em;margin-bottom:0.5em;">groove</div>
- <div style="border-style:ridge;padding:0.25em;margin-bottom:0.5em;">ridge</div>
- <div style="border-style:hidden;padding:0.25em;margin-bottom:0.5em;">hidden</div>
- <div style="border-style:none;padding:0.25em;margin-bottom:0.5em;">none</div>


### Border Color

The final property that defines borders is "**border color**" (`border-color: `).

Border color, like `color: ` and `background-color: `, accepts an rgb(), rgba(), hex, or other color value.
