---
title: Multiple Sources
module: topic-06
permalink: /docs/topic-06/audio-multi-src/
redirect_from: /docs/topic-06/10-audio/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

When using more than just `.mp3` you should include multiple versions of the file, with decreasing preference. This allows the browser to then use the file format that it supports.

#### src

This can be done by omitting the `src=""` attribute from the `<audio>` element and instead using a separate `<source>` element inside the parent `<audio>` element.

The `<source>` element is an empty element, and accepts the `src=""` attribute to provide the URL to the browser.
