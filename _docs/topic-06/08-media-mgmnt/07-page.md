---
title: Making Hosting Decisions
module: topic-06
permalink: /docs/topic-06/media-decisions/
redirect_from: /docs/topic-06/08-media-mgmnt/07-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are several things to consider when deciding to host your media on your own site or through a third-party:


### Affordability

As discussed on the previous pages, hosting your own media can take up bandwidth. Increasing bandwidth with service providers and hosting companies usually comes at a hefty price.


### Converting Files

Third-party hosting converts files for you, and increases the compatibility of the media across browsers. This is not to say that you can't provide your own alternative media and conversions, but it can take time. As stated, **always test your site across as many browsers and devices as possible to ensure the page is rendering as intended.**

In terms of downloading files from other sources, you likely will not have access to the original file. For example, with audio, to export an .ogg file (whether it's a song you own or have recently sourced), you may need to use an online converter like [Convertio](https://convertio.co/mp3-ogg/) or [Zamzar](http://www.zamzar.com/convert/mp3-to-ogg/). Again, this is only a band-aide; ideally, you're providing your own created audio (music, recordings, sound effects, etc) which you can export as an .ogg legally.

A similar process is needed to create .webm video files. Certain plugins can be downloaded for video editors like Adobe Premiere so that you can export .webm files without a band-aide conversion.


### Content Protection

You saw how easy it is to download files from `<video>` and `<audio>` elements on the previous page.

If content protection is important, you should use a third party service, such as [Bandcamp](https://bandcamp.com/). These services have a vested interest in protecting the content on their servers.

The use of these services may also increase browser compatibility, as they want to ensure their content is available to everyone. This means you don't have to worry about browser compatibility issues as much!


### Exclusion Rules

If the content needs to be exclusive to your site, and not available through a third-party site such as YouTube, then you must host the file. You will need to research current best-practices for self-hosting protected content.


### Final Decision

You will need to be aware of all of these options and potential problems and weight all of the requirements of your project to determine the most appropriate route.
