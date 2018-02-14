---
title: Links to Outside Sites
module: topic-04
permalink: /docs/topic-04/links-to-others/
redirect_from: /docs/topic-04/45-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

_Remember?_ Links that include the “`http/https`” as part of the entire URL are known as **absolute URLs**.

<div id="code-heading">HTML</div>
```html
<a href="https://www.site.com" target="_blank">Site</a>
```

Notice in the above link that it includes “`https`”. The “`https`” is required to signify to the browser that this is an ‘external’ link outside of the current document’s directory/server. **You must include either “`http`” or “`https`”.**

The former is a older, established, version of the “hypertext transfer protocol”, which specified how data was sent between clients. The latter, is a “secure” version of this protocol. Whenever possible, you should provide “`https`” links (just check that they work first), as it provides a safer browsing experience.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="zEwMLb" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Intro-Web-Dev] Topic-05: Links Pt. 3" class="codepen"></p>
</div>
