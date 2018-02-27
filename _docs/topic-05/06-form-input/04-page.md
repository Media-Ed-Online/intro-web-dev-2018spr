---
title: Name
module: topic-05
permalink: /docs/topic-05/input-name/
redirect_from: /docs/topic-05/06-form-input/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">
      <span class="sr-only">75% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><input type="..."</span> <span style="color: #79AF33; font-weight: bold;">name="..."</span> <span style="color: #999">id="..." /></span></p>
  </div>
</div>


Each form control requires a `name=""` attribute. This information is sent as part of a "name:value" pair to the server.

For example, an input element with the **name** attribute set to "username" (i.e. `name="username"`) might collect the data "Justine", which would then be sent to the server as `username:Justine`.
