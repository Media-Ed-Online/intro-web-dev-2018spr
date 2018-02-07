---
title: The Internet of Yesteryear
module: topic-03
permalink: /docs/topic-03/wayback/
redirect_from: /docs/topic-03/22-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

![Google as a snail-mail service](../img/google-classic.jpg)

The Wayback Machine allows you to see what certain websites looked like at different points in history. This may not be the best resource for learning how to code a website, but it does allow you to get a sense for how a company may have viewed their brand over time, how the web used to look, or retrieve information from the past that is no longer live. It's also the coolest way to spend a Saturday night.

The resource is the Internet Archives [Wayback Machine](https://archive.org).

<ul class="nav nav-tabs">
  <li class="active"><a href="#step1" data-toggle="tab">Chrome</a></li>
  <li><a href="#step2" data-toggle="tab">Firefox</a></li>
  <li><a href="#step3" data-toggle="tab">Safari</a></li>
</ul>
<div id="myTabContent" class="tab-content">
  <div class="tab-pane fade active in" id="step1">
    <p>In Chrome, if you right click, you can select “inspect” which will bring up the Chrome developer tools to the right.</p>

    <p>You can use the “Elements” tab, to see source code, as well as the matching highlighted element in the actual page (as described below in Safari). You can also select the “Source” tab to see the raw course code files. Again, these allow you to see the code that creates the page your are viewing.</p>

    <img src="../img/inspect-with-chrome.png" alt="Example of Inspecting Code in Chrome" />
  </div>
  <div class="tab-pane fade" id="step2">
    <p>You can do the same thing in Firefox as Chrome. Simply right click in the page you want to see the code for, and select either “View Page Source”, which loads the file in a separate tab, or “Inspect Element”, which open up a more complete set  of developer tools.</p>

    <img src="../img/inspect-with-firefox.png" alt="Firefox developer tools" />
  </div>
  <div class="tab-pane fade" id="step3">
    <p>To inspect code in Safari, you first need to make it so you can see the developer tools. To do this:</p>

    <ol>
      <li>Open preferences (<code>cmd</code> + <code>,</code>).</li>
      <li>Go to the advanced tab.</li>
      <li>Select “Show Develop menu in menu bar.”</li>
    </ol>

    <img src="../img/inspect-with-safari-1.png" alt="Example of how to turn on develop menu" />

    <p>This will cause a tab to appear in your menu bar. You can now select this menu tab, then select “Show Page Source.”</p>

    <img src="../img/inspect-with-safari-2.png" alt="Example of how to pull up page source in safari" />

    <p>This will bring up a separate window/tab where you can navigate around all of the resources sent over to your browser for the specific web page.</p>

    <p>You can also select the “Elements” tab from within this window. This alternative view of the code allows you to see where each html element is in the displayed page. As you move your mouse through the code, various parts of the page will highlight, representing the current element in the code you are inspecting.</p>
  </div>
</div>
