---
title: Action
module: topic-05
permalink: /docs/topic-05/form-action/
redirect_from: /docs/topic-05/05-form-intro/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="50" aria-valuemin="0" aria-valuemax="100" style="width: 50%">
      <span class="sr-only">50% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><form</span> <span style="color: #79AF33; font-weight: bold;">action="#"</span> <span style="color: #999">method="..." id="..." class="..."> ... </form></span></p>
  </div>
</div>


The `action` attribute is a link to a server-side script (i.e. a file on another computer, not the users computer). Typically this file is code file (php, javascript, python, java, etc) on a server that will do 'something' with the user data before returning information back to the browser.

<span class="label label-info">NOTE:</span> The value of the action attribute will always be an URL.
