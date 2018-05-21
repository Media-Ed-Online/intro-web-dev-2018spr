---
title: Margins in Practice
module: topic-10
permalink: /docs/topic-10/margin-example/
redirect_from: /docs/topic-10/05-margin/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />


In the following example, look at the two containers and how the are positioned based on the margin settings.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="gXLVyW" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Margin, Pt. 1" class="codepen"></p>
</div>



### Margin and Padding Combined

In the next example, notice how the `.child-container-03`, has both margin and padding properties set. Also notice, that the parent-container has neither. Note that the browser does not allow the child container's margin to push the height of the parent container. However, it does still create space between the top of the containing window and both the parent and child elements.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="RjKboZ" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Margin, Pt. 2" class="codepen"></p>
</div>


### Using Margin to Set Center Alignment

The margin property is also used to center align element, horizontally, in there parent elements. This can be accomplished by setting the properties value to `auto`, or by setting both `margin-left: auto;` & `margin-right: auto;`.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="VrPZWb" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Margin, Pt. 3" class="codepen"></p>
</div>
