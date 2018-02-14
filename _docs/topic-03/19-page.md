---
title: Ignoring Empty Space
module: topic-03
permalink: /docs/topic-03/empty-space/
redirect_from: /docs/topic-03/19-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Almost all non-heading text will be placed within a paragraph element in a web document.

<div id="code-heading">HTML</div>
```html
<p>This is a paragraph element.</p>
```

<br />

Compare this to Markdown:
<div id="code-heading">markdown</div>
```markdown
This is a paragraph.

In markdown, a paragraph requires no extra markup to signify it as such. An empty line between text blocks signifies a new paragraph.
```

### Empty Space

You'll notice that when using _Markdown_, empty lines create paragraphs and provide padding between one paragraph and the next. This is not true of HTML.

By default, browsers will remove empty spaces from paragraph element blocks. This is true of spaces and extra empty lines. You need to be aware that you cannot change the output of your rendered HTML code by adding extra spaces or lines unless you code for them; simply pressing space bar or return won't cut it.

The following will both display as single line paragraphs after being rendered.

<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="qXwEbW" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-01: Paragraphs 1" class="codepen"></p>
</div>
