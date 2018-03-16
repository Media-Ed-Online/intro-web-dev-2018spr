---
title: Adding Link Content
module: topic-07
permalink: /docs/topic-07/basic-nav-li/
redirect_from: /docs/topic-07/03-basic-nav/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

To add links using HTML structural elements, you'll need to weigh appearance versus accessibility.


### Flat Text

To get a "horizontal" nav without much styling, you can simply add `<a href="">` contents, separated with a visual signifier like vertical bars ( \| , written with escape name `&vert;` ),  interpunct ( &middot; , written with escape name `&middot;` ), or additional spaces ( each created with escape name `&nbsp;` ).

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="qoNKjY" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-07: Basic Navigation, Pt. 1" class="codepen"></p>
</div>


### Lists

However, lists are preferred by screen-reader technologies as it increases the accessibility of the navigation.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="oqLyeP" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-07: Basic Navigation, Pt. 2" class="codepen"></p>
</div>

<span class="label label-info">NOTE:</span> Adding the property `li {display: inline}` to the page `<style>` will visually align the list items horizontally like the previous option, without sacrificing accessibility.
