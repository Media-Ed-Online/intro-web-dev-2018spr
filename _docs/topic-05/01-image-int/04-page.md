---
title: Alt
module: topic-05
permalink: /docs/topic-05/img-alt/
redirect_from: /docs/topic-05/01-image-int/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Proper style and accessibility standards dictate that you should always include the **alternative text attribute**. The key for this is simply `alt=""`. The value in the double quotes should describe the image. This description is used by screen readers for those who are visually impaired.


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="45" aria-valuemin="0" aria-valuemax="100" style="width: 45%">
      <span class="sr-only">45% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><img src="#"</span> <span style="color: #79AF33; font-weight: bold;">alt="..."</span> <span style="color: #999">title="..." width="..." height="..." /></span></p>
  </div>
</div>


Therefore it is critical that you provide a detailed description, especially in the case where the image is necessary to understand the content of the page.

- Poor: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`alt="Me getting help."`
- Better: &nbsp;`alt="Justine receiving help from an instructor while at a computer."`
