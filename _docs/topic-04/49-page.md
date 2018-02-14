---
title: Page to Page
module: topic-04
permalink: /docs/topic-04/page-to-page/
redirect_from: /docs/topic-04/49-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Relative URL's help with building a site locally before pushing it to the web. This way you can develop on your local machine, and still have links to pages be valid.

<div style="display: inline-block; width: 100%;">
  <img src="../img/directory-relative-urls.jpg" style="float: right; width: 250px; margin: 0 0 5px 5px; border: none" />

  <p>But how do we navigate to a different directory using a relative URL?</p>
  <p>Well, if a single "<code>.</code>" states that we need to remain in the current level of our directory heirarchy, two "<code>..</code>" is effectively saying <i>"to find this file, begin here and then step back a directory."</i></p>

  <p>Consider this example. We have a three-page site, with an <b>index.html</b> in the root directory, and two pages, <b>about.html</b> and <b>contact.html</b> in the child-directory <b>/pages</b>. I have a menu at the top of each page that needs to link to each of these pages despite what page the visitor is currently on. So how do I do this?</p>
  </div>

Here are some ways you would link these files:
- From Index to About: `<a href="./pages/about.html">To About</a>`
- From About to Contact: `<a href="./contact.html">Contact Me</a>`
- From Contact to Index: `<a href="../">Back to Home</a>`
