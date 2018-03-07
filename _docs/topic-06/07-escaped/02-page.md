---
title: Codes
module: topic-06
permalink: /docs/topic-06/esc-codes/
redirect_from: /docs/topic-06/07-escaped/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Escape codes always start with an ampersand (`&`) character followed by the individual code and finished with a semicolon (`;`).

### Character Code

All characters have a numerical, [decimal-based](https://www.w3schools.com/charsets/ref_utf_basic_latin.asp) (in addition to hexadecimal), value. In HTML, prepend decimal this value with the ampersand identifier as well as a number sign (`&#`).

Using escape character codes in HTML text is straight forward. Simply replace the character you want with its escape code equivalent in the text.

For example, we could write the word "CAT", by wrapping the individual letter's decimal values (67, 65, and 84) in the escape code values as;

<div id="code-heading">HTML</div>
```html
<h1>Where is the &#67;&#65;&#84; ?</h1>
```

<div class="displayed_code_example">
    <h1>Where is the &#67;&#65;&#84;?</h1>
</div>
