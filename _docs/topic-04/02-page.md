---
title: Comments in HTML
module: topic-04
permalink: /docs/topic-04/html-comments/
redirect_from: /docs/topic-04/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Comments are designated slightly different in every language. In HTML however, as with everything else, they are designated using a **tag**. Anything placed within this tag will be ignored by the browser.

<p><span class="label label-info">NOTE:</span> Comments are not hidden from other <i>people</i>. Comments, if included in your deployment code, will be available for the whole world to see.</p>

<div id="code-heading">HTML</div>
```html
<!-- This is an HTML comment. -->
<!-- Everything placed between the 'dashes' is part of the comment. -->

<!-- Comments should not span multiple lines in HTML.
        Sometimes this can cause issues for a browser's processor.

        This comment is considered as bad style. -->

<!-- Instead: -->
<!-- You should place each line of a multi-line comment within a comment tag. -->
<!-- That would be considered proper style. -->
```
