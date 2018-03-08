---
title: Styling
module: topic-06
permalink: /docs/topic-06/id-style/
redirect_from: /docs/topic-06/01-id-att/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

In HTML, the following style guide and naming conventions should be used for ID's:

- _HTML Value Quotation Marks_ - You should surround your ID value using double quotation marks (as opposed to single).
- _ID Naming_ - Use meaningful ID names that reflect the purpose of the element in question, like "contact" rather than "paragraph4".
- _Acceptable Characters_ - Technically, in HTML5, ID names must contain at least one character and no spaces. Which leaves all [UTF-8](https://www.w3schools.com/charsets/ref_html_utf8.asp) characters as options. (i.e. `a-z`, `A-Z`, `0-9`, "`_`", "`-`", "`:;,?!@#$%^&*+`", etc.).

  However, due to issues that can arise in element selection with CSS and JavaScript, you should follow a more restrictive naming conventions. These conventions are also intended to lend consistency to code between pages and developers, as well as increase readability.

    1. Use lowercase letters or number (i.e. `a-z` and `0-9`).
    2. Start an ID name with a lowercase letter.
    3. Use hyphens ("`-`") to separate words (as opposed to underscores "`_`" or [camelCase](https://en.wikipedia.org/wiki/Camel_case)).


<div id="code-heading">HTML</div>
```html
<!-- Recommended: -->
<div id="use-double-quotations">
<div id="contact">
<div id="image-gallery-1">

<!-- Bad Style: -->
<div id='do-not-use-single-quotations'>
<div id='paragraph4'>
<div id='Image_Gallery-1!'>
```

<span class="label label-info">NOTE:</span> You should use ID names that are as short as possible, but as long as necessary. The goal is to clearly convey what the element is without being unnecessarily verbose.
