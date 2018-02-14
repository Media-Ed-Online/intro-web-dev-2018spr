---
title: Burrito Those Tags
module: topic-04
permalink: /docs/topic-04/burrito-tags/
redirect_from: /docs/topic-04/55-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

We "wrap" elements in opening and closing tags, as you know. You're now familiar with single-tag element sets like `<p>...</p>`, but elements can actually have multiple sets of tags. It's considered proper to layer these sets in concentric orbits around the element.

This basically looks like `<tag3><tag2><tag1>...</tag1></tag2></tag3>`

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>

<html>
  <body>

    <!-- From a recently released deleted scene: -->
    <p>Spengler: "There's something very important I forgot to tell you."</p>
    <p>Venkman:  "What?"</p>
    <p>Spengler: "Dont cross the streams."</p>
    <p>Venkman:  "Why?"</p>
    <p>Spengler: "It would be bad."</p>
    <p>Spengler: "Almost as bad as <u><i>improperly nesting HTML tags.</u>"</p></i>
    <p>Venkman:  "What's proper?"</p>
    <p>Spengler: <u><i>"This."</i></u>.</p>
    
  </body>
</html>
```

<a href="https://youtu.be/jyaLZHiJJnE" target="_blank">True story<a/>.
