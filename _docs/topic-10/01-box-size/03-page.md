---
title: Sizing with Percentages
module: topic-10
permalink: /docs/topic-10/box-size-percent/
redirect_from: /docs/topic-10/01-box-size/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Another way of specifying size of boxes is through percentages. Percentages work by being the percent specified of the _parent_ element.

If the parent element is `<body>...</body>` then the elements width can be set using a percentage, and it will stay in relation to the size of the page. However, the height must be set using an absolute value still.

In the following example, the parent-container or outer-box is set to be 66% the width of the window or parent example container in this example. There is no height property given. So instead, it is made tall enough by the browser to hold its content.

The 'inner-box' is set to be 75% of the width, and 50% of the height of the 'parent-container.'

**NOTE:** Change the width of your browser window and notice the ability of the example to resize accordingly.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="qVqgxR" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Box Models, Pt. 2" class="codepen"></p>
</div>


Now that our boxes can resize in relation to the screen, we will have to be careful about setting absolute sizes. The following is the same example as the previous _EXCEPT_ the height of the 'parent-container' is set to 300p pixels. There is also more text. Notice, that when you make your browser window narrow, the text spills out of the element. This is plain example of bad web design.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="VrmRZX" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Box Models, Pt. 3" class="codepen"></p>
</div>
