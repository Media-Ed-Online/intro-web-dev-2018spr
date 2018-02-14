---
title: Definitions
module: topic-04
permalink: /docs/topic-04/definition-lists/
redirect_from: /docs/topic-04/39-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Definition lists are used to define terms. A definition list is identified with `<dl>...</dl>` tags.

The term being defined is encapsulated in "definition term" tags (`<dt>...</dt>`).

The terms definition is then encapsulated in the "definition" tags (`<dd>...</dd>`).

<span class="label label-info">NOTE:</span> Sometimes you might see a list where there are two terms used for the same definition or two different definitions for the same term. This is acceptable.


<div id="code-heading">HTML</div>
```html
<p>Definition lists look much like other HTML lists.</p>
<dl>
  <dt>Term 1</dt>
  <dd>This is the definition of Term 1.</dd>
  <dt>Term 2</dt>
  <dd>This is the definition of Term 2.</dd>
</dl>
```


<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="ZrJoYm" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-04: HTML Lists Pt. 3" class="codepen"></p>
</div>
