---
title: Solving Conflicts
module: topic-06
permalink: /docs/topic-06/esc-about/
redirect_from: /docs/topic-06/07-escaped/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

As you may have discovered, HTML specifies that certain are "reserved" or serve a special purpose for browsers. The most obvious conflicts are the greater than and less than characters (`<`, `>`), since these identify tags to browsers in HTML. Any character that may be accidentally interpreted as markup by the browser _should_ be replaced with its escape code equivalent. There are also characters that have no easy "keyboard" equivalent, (such as the copyright symbol - &#169; ) in which case an escape code must be used.

<p style="margin-left: 30px;"><b>Question:</b> So what is a developer to do if they need to write some math (or something else less stressful than including comparison operators in their page)?</p>

<p style="margin-left: 30px;"><b>Answer:</b> Use special codes, known as escape characters, that the browser can use to render the intended character!</p>

This is not a fun process, but one that is necessary since HTML is a language.

**NOTE:** Also, for those of you who are more "security" minded or wanting to protect yourself and your client from "middle-man" attacks, using escape characters is critical, as evidence by [some discussions around the web](http://wonko.com/post/html-escaping).
