---
title: The Head Element
module: topic-03
permalink: /docs/topic-03/head-element/
redirect_from: /docs/topic-03/12-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

## `<head>...</head>`

The _head_ element is a container for processing information and document metadata. This will include elements that may link to other files, hold the author information, and pass the name of the page to the processor. The _head_ contains high-level information about the site, and always comes first within the root element.

In many aspects, the contents are not visible to site visitors. Rather, the _head_ contains information for indexing the site, like for search results. Certain elements in the _head_ can also help dictate how the page will visibly look. In this sense, we can consider the _head_ to contain the thoughts of the page.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```


### `<title>...</title>`

The _title_ tag is the only **required** element within the _head_, and aptly contains your site's or page's title.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Way-Cool Awesome Site</title>
    <!-- Meta data and information about your site, not visible to visitors. -->
  </head>

</html>
```
