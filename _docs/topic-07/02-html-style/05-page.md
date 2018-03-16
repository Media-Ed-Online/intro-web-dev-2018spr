---
title: Images
module: topic-07
permalink: /docs/topic-07/html-style-placement/
redirect_from: /docs/topic-07/02-html-style/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Images have certain behaviors within a page, including how and where they appear and react with surrounding and nearby elements. To declare images in the `<style>` element, use the element selector `img {}`.

 You'll remember that images are [block-level](../../topic-06/div-style/) elements, and "stack" with other block-level elements down the page. To override this "stacking," you can use the `float: ` property to effectively direct the flow of adjacent elements. For example, using `float: left` will place the image to the left, and elements below will flow around it. The opposite is true of `float: right`.

<span class="label label-info">NOTE:</span> You can also use `img {}` to style the size of your images across the page, saving you the need to set the width and height in each `<img />` tag.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="bveMWm" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="bveMWm" class="codepen"></p>
</div>
