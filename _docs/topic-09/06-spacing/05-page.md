---
title: Word Spacing
module: topic-09
permalink: /docs/topic-09/word-spacing/
redirect_from: /docs/topic-09/06-spacing/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

In addition to being able to adjust the space between characters, developers can adjust the amount of space between words only, using the `word-spacing: ` property.

<div id="code-heading">CSS</div>
```css
* {
  word-spacing: normal;
}
```

`word-spacing:` accepts these term values:
- `normal` (default, 0.25em)
- pixels (`px`)
- points (`pt`)
- percent (`%`)
- ems (`em)`
- ...most other size terms, including negative values


### “Why adjust word spacing?”

Like with `letter-spacing: `, changing the distance between words and shift the visual message of the text as part of branding or design work. Fonts are are wider can generally see a decrease in `word-spacing: ` without sacrificing too much legibility, although this should be a thoughtful decision.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="Bxogoe" data-default-tab="css,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="[Topic-09] Word-Spacing (Toggle)" class="codepen"></p>
</div>
