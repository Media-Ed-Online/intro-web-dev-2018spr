---
title: Basic Positioning
module: topic-08
permalink: /docs/topic-08/intro-positioning/
redirect_from: /docs/topic-08/10-using/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Designing layout is an intensive process, and is where most of your time will be spent as a dev. There are many advanced properties that will help you when creating layouts (particularly those that need to be responsive), but for now, let's consider creating a _static_ layout using **absolute positioning**.

The position property (`position: `), as you may expect, allows developers to specify where the position of elements will be within the browser window.

_Absolute positioning_ (`position: absolute`) sets elements absolutely, removing them from the normal flow (remember our discussion on [block-level](../../topic-06/div-element/) elements?). For our purposes, we can use absolute positioning and math to crudely "draw" on the page without having to do much page building.

For example, I can create a "canvas" 100px by 100px wide, and color half using a rectangle half the size of the parent, and half its distance across:

<div id="code-heading">HTML</div>
```html
<head>
  <style>
    .canvas {
      background-color: black;
      height: 100px;
      width: 100px;
      position: absolute;
    }
    .rectangle {
      background-color: red;
      height: 100px;
      width: 50px;
      position: absolute;
      left: 50px;
    }
  </style>
</head>

<body>
  <div class="canvas">
    <div class="rectangle"></div>
  </div>
</body>
```


#### Example

**Geometric Style:** The following example, I created a "canvas" 400px by 400px, with 3 main elements - the sun, rainbow, and clouds. All of these elements were positioned _absolutely_ to the **bottom** and **left** of the canvas' edges and the neighboring element.


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="VXOLVW" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Basic Absolute Positioning" class="codepen"></p>
</div>

<br/>

**Realism-ish Style:** Alternatively, I placed all of my colored blocks in an additional `.curved` class, with the border-radius property (`border-radius: `) set to a high curvature. It may look more like a rainbow, but more calculation required with this method, sizing in terms of the left, top, and right pixel values.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="bvyVbO" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Basic Absolute Positioning, Pt. 2" class="codepen"></p>
</div>
