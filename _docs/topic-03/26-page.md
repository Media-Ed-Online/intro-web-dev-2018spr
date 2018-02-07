---
title: File- vs Directory-Based URLs
module: topic-03
permalink: /docs/topic-03/file-v-direct-urls/
redirect_from: /docs/topic-03/26-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are serveral ways we can control how our `html` files are retrieved, and how they appear in the address bar of a web browser.

Take the example file **about.html**. We can place it where it can be accessed:

<br />

<ul class="nav nav-tabs">
  <li class="active"><a href="#step1" data-toggle="tab">Via the Root</a></li>
  <li><a href="#step2" data-toggle="tab">Via a Child Directory</a></li>
  <li><a href="#step3" data-toggle="tab">Via Referenced Files</a></li>
</ul>
<div id="myTabContent" class="tab-content">
  <div class="tab-pane fade active in" id="step1">
    <div style="display: inline-block; width: 100%;">
      <img src="../img/directory-about-root.jpg" style="float: right; width: 250px; margin: 0 0 5px 5px; border: none" />
      <p>This assumption allows for the publication of "clean URLs," as we do not need to explicitly include the <code>index.html</code> at the end of the URL. This is not to say that we could not have additional pages that we explicitly address. For example we could have additional html pages at the same directory level, such as an <code>about.html</code>.</p>

      <p>The URL for this case would look like <code>baseurl.com/about.html</code>.</p>
    </div>
  </div>
  <div class="tab-pane fade" id="step2">
    <div style="display: inline-block; width: 100%;">
      <img src="../img/directory-about-folder.jpg" style="float: right; width: 250px; margin: 0 0 5px 5px; border: none" />
      <p>However, if you wished to have a “cleaner” looking URL, you could create an additional child directory labeled <code>/about</code> and place an <code>index.html</code> within that directory. </p>

      <p>The URL for this case would look like <code>baseurl.com/about/</code>. Notice how we do not use the <code>.html</code> and instead the URL ends with a directory slash.</p>
    </div>
  </div>
  <div class="tab-pane fade" id="step3">
    <div style="display: inline-block; width: 100%;">
      <img src="../img/directory-about-pages.jpg" style="float: right; width: 250px; margin: 0 0 5px 5px; border: none" />
      <p>For our class, we will create some of our <b>/ assignment</b> and <b>/ project</b> directories with a sub-directory called <b>/ pages</b>. It will contain all of our additional <code>.html</code> pages, not any of which will be called <code>index.html</code>.</p>

      <p>This is good for those of us learning directory structure for the first time, but because these sub-directories will not have an <code>index.html</code> file to request, <code>baseurl.com/pages/</code> will most likely return a 404 error.</p>

      <p>The URL for this case would look like <code>baseurl.com/pages/about.html</code>.</p>
    </div>
  </div>
</div>
