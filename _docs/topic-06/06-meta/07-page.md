---
title: Robots
module: topic-06
permalink: /docs/topic-06/meta-robots/
redirect_from: /docs/topic-06/06-meta/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The robots name type tells browsers whether they may spider or crawl the published webpage.

This name type takes one of four acceptable content values. The `noindex` value prevents a page from being indexed, and `nofollow` prevents links from being crawled. The `noarchive` value instructs a search engine not to store an archived copy of the page, and `nosnippet` asks that the search engine not include a snippet from the page along with the page's listing in search results.

<div id="code-heading">HTML</div>
```html
<meta name="robots" content="nofollow">
```
