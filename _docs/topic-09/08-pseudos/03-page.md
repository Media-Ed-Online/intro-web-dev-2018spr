---
title: Pseudo-Classes
module: topic-09
permalink: /docs/topic-09/pseudo-classes/
redirect_from: /docs/topic-09/08-pseudos/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

A **pseudo-class** can be added to an element to style it _only_ during certin conditions. Additional CSS rules can be applied to the page so that when an an event is triggered (like clicking on something), the element visually changes for users.

This is the same technology that allows browsers to alter the appearance of links when you hover over them, click them, or after you have visited them.

The pseudo-classes usually attached to links are:
- `:link` (default, an unvisited link)
- `:visited` (how the link looks after being visited)

Like pseudo-elements, pseudo-classes are appended after a CSS selector.

<div id="code-heading">CSS</div>
```css
a:link {}
a:visited {}
```

The web was built with links, for links, on links. They are fundamental to the infrastructure of any site. If you have a large amount of links, it is considered good practice to help visitors track their progress by setting the unvisited and visited style to your links.

<span class="label label-info">NOTE:</span> You can also style links using their element selector (`a {}`), although it is more generalized than `a:link`.

### “Why would I style links?”

<a href="https://en.wikipedia.org/wiki/Hyperlink#How_hyperlinks_work_in_HTML" target="_blank" style="color: blue">Links are ugly,</a> or rather, their default styling - while functional - is not usually aesthetically-pleasing. Browser defaults don't often mesh with site designs, and most designers will style links to better fit the pallet of the site.

<span class="label label-danger">IMPORTANT:</span> A word of caution, however. While default link styling isn't the most attractive, it is rooted in internet culture and user experience. Styling that is too far removed form the norm can be disorienting and unpopular, as Google found out with its “<a href="https://mashable.com/2016/05/09/google-black-links/#dRWYeUgxc5qU" target="_blank">black link</a>” experiment in 2016.

In the example below, the link should turn to gray after you visit it (it will open in a new tab/window).

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="KywzgB" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-08] Pseudo-Classes, Pt. 2" class="codepen"></p>
</div>
