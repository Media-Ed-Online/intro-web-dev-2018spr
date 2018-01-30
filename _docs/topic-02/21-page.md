---
title: Internal Linking
module: topic-02
permalink: /docs/topic-02/link-internal/
redirect_from: /docs/topic-02/21-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

## Relative Linking Within Your Repository

As you now know, the internet is built foundationally on links and inter-connected files and systems. We'll get into **hypertext** and **hyperlinks** later on in the course, but for right now, let's continue the [discussion on URL types](/docs/topic-02/urls/) and look at linking the files withing our directory together.

You've done some linking in **markdown** already, using outside sources and _absolute_ URLs:

```markdown
[discussion on URL types](https://media-ed-online.github.io/intro-web-dev/docs/topic-02/urls/)
```

<br />

But I can also link to pages in this website using _relative_ URLs, as long as I stay within my  `/intro-web-dev` repository. As the adminstrator of this site, I can link to the same page like so:

```markdown
[discussion on URL types](/docs/topic-02/urls/)
```

<br />
If within our _Intro-Web-Dev_ repo, I can use either of these methods to link back to the same page. But one is much more efficient for me to type, and doesn't require me to have pushed all of (or anything) to GitHub's servers yet.
