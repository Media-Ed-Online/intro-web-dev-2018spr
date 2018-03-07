---
title: The Meta Element
module: topic-06
permalink: /docs/topic-06/meta-about/
redirect_from: /docs/topic-06/06-meta/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

If you remember from a few Topics back, we explored how meta elements are placed inside of the `<head>` element, and briefly described what role they perform. Let's dig a littler deeper into this concept.

The `<meta>` element describes metadata about an HTML page. This **metadata is not displayed to users**, but used by browsers and search engines. This may describe  what character encoding the document contains, the published date, author information, descriptions for search engines, keywords, etc.

The `<meta>` element is an "empty element". As such, no closing tag is necessary. Also, as with form elements, metadata is always passed as a name:value pair. Typically via the `name=""` and `content=""` attributes.

**NOTE:** `<meta>` elements are _always_ placed inside the `<head>` element.
