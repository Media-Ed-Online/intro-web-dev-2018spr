---
title: Making Hosting Decisions
module: topic-06
permalink: /docs/topic-06/media-decisions/
redirect_from: /docs/topic-06/08-media-mgmnt/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are several things to consider when deciding to host your media on your own site or through a third-party:

### Content Protection

One of the potential issues of using the `<audio>` element in particular is that it allows end-users to easily download the audio file. For example, in Safari, this can be done by right-clicking the audio player and selecting "Download Audio." Chrome actually provides a download button with the audio player.

<center><img src="../imgs/safari-dl-audio.jpg" title="How to download audio in Safari" width="400" style="border: 0" /></center>

If content protection is important, you should use a third party service, such as [Bandcamp](https://bandcamp.com/), [SoundCloud](https://soundcloud.com/), or the like. These services have a vested interest in protecting the content on their servers.

The use of these services may also increase browser compatibility, as they want to ensure their content is available to everyone. (**Read:** This means you don't have to worry about browser compatibility issues as much!)


### Exclusion Rules

If the content needs to be exclusive to your site, and not available through a third-party site such as YouTube, then you must host the file. You will need to research current best-practices for self-hosting protected content.


### Final Decision

You will need to be aware of all of these options and potential problems and weight all of the requirements of your project to determine the most appropriate route.
