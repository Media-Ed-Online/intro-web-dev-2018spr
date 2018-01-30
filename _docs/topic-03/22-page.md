---
title: Inspection and History
module: topic-02
permalink: /docs/topic-02/inspection/
redirect_from: /docs/topic-02/21-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

One invaluable resource for web developers is the ability to look at the code for websites you visit. Browsers get code from servers, which means you can look at this code to try and inspect how someone else might have solved a problem.

_During Workshops, you are expected to look at each other's codes as Peer Reviewers, looking for errors and code choices._

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
