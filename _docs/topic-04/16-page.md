---
title: Viewport
module: topic-04
permalink: /docs/topic-04/head-viewport/
redirect_from: /docs/topic-04/16-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<img src="../img/meta-viewport.png" alt="two screens, one with viewport set" style="width: 250px; margin: auto;" />

The rise of mobile devices changed how we view and build for the web. HTML5 introduced a method to let web designers take control over the viewport, through the `<meta>` tag.

The viewport is the user's visible area of a web page. It varies with the device, and will be smaller on a mobile phone than on a computer screen.

You should include the following `<meta>` viewport element in all your web pages:

<div id="code-heading">HTML</div>
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

A `<meta>` viewport element gives the browser instructions on how to control the page's dimensions and scaling.

The `width=device-width` part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The `initial-scale=1.0` part sets the initial zoom level when the page is first loaded by the browser.

We will discuss this property more when _Responsive Web Design_ is introduced. In the meantime, include this in your head elements so that your pages display more appropriately on mobile browsers.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta name="description" content="Head Elements in HTML">
    <meta name="author" content="Justine Evans">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>

</html>
```
