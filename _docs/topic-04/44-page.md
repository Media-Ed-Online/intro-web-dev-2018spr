---
title: Targeting How the Link Opens
module: topic-04
permalink: /docs/topic-04/new-window/
redirect_from: /docs/topic-04/44-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The **target** attribute provides us a way of specifying to a browser how a link will open in the browser. The default behavior is to open the linked document in the same window/tab from which is was clicked. If manually included, the attribute's value would be set to `"_self".`

Other values include:
- `"_blank"` - Opens the linked document in a new window or tab
- `"_parent"` - Opens the linked document in the parent frame
- `"_top"` - Opens the linked document in the full body of the window
- `"framename"` - Opens the linked document in a named frame


<div id="code-heading">HTML</div>
```html
<a href="URL" target="_blank">link text</a>
```

<div class="codepen-embed">
  <p data-height="200" data-theme-id="30567" data-slug-hash="yzbMvB" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-05: Links Pt. 2" class="codepen"></p>
</div>
