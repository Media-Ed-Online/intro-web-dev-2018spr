---
title: Z-Index in Practice
module: topic-10
permalink: /docs/topic-10/z-index-example/
redirect_from: /docs/topic-10/09-z-index/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The following example comes from an [article on the Mozilla Developers Network](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Positioning/Understanding_z_index/Adding_z-index).

Notice a few things about this example.

1. `DIV #1` was given a position value of `absolute` and `z-index: 5`.
    - This is causing it to be placed on top of all other elements.
    - Even the yellow element `DIV #5`. That is because the yellow element did not have a position property setting.
4. Likewise, `DIV #4` is also placed on top of the yellow `DIV #5` element.
5. The green `DIV #2` is placed on top of `DIV #4` since it has a higher z-index, but underneath `DIV #1`.
6. The blue, `DIV #3` was placed underneath all other elements, even the yellow `DIV #5`.
    - This is because it was given a negative z-index (`-2`).
    - This allows it to be placed under `DIV #3`, even though `DIV #3` cannot be placed above other elements with position values specified.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qVRGZE" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09]  Z-Index" class="codepen"></p>
</div>
