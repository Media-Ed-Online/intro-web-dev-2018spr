---
title: Using Links
module: topic-04
permalink: /docs/topic-04/href/
redirect_from: /docs/topic-04/43-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

With **links** being such a basic and historical part of the Internet, they  also have a very simple tag; `<a>...</a>`. Any text between a hyperlink element’s tags will display as “hypertext”. Traditionally, this has been blue, underlined text, visually signifying to the user that the text is a <a href="#" style="color: blue; text-decoration: underline">link</a>.

In order to link to another document, the author must include a hyper-reference attribute within the opening tag. This attribute is signified with `href=""`.

<div id="code-heading">HTML</div>
```html
<a href="URL">link text</a>
```

<span class="label label-info">NOTE:</span> Link text should be specific about where the user will be going if they click a link. This means that links **should not** be simple text such as "[Click Me!](#)" Instead, good style would dictate that the link text be a description of the site, name, or information that informs the user.


<div class="codepen-embed">
  <p data-height="200" data-theme-id="30567" data-slug-hash="aLWJpd" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-05: Links" class="codepen"></p>
</div>
