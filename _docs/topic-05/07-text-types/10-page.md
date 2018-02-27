---
title: Autofocus
module: topic-05
permalink: /docs/topic-05/text-autofocus/
redirect_from: /docs/topic-05/07-text-types/05-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The `autofocus` attribute is used to set the "focus" of a browser to the specified form element after the page loads.

Refresh the page. See how the cursor is blinking inside the first example input box? This means it is "focused," and can take input right away.


<div id="code-heading">HTML</div>
```html
<p>
  Password:
  <input type="password" name="password" id="test-password" autofocus />
</p>
```

<div class="row" style="margin-top: -30px;">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-success">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-check-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Please Enter:
          </h4>
        </div>
          <div class="panel-body">
            <p style="font-size: large;">
              <span style="margin-right: 1em;">Birth Year:</span>
              <input type="text" name="name" id="test-date" maxlength="4" size="4" value="19" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 2.6em;">Net ID:</span>
              <input type="text" name="name" id="test-text" placeholder="ab123456" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 1.2em;">Password:</span>
              <input type="password" name="password" id="test-password" maxlength="15" autofocus/>
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 1.26em;">Comments or Concerns:</span>
              <textarea name="comments" id="test-textarea" cols="20" rows="4" style="width:100%; border-color: #D8D8D8 !important; color: #777; font-size: medium">Enter up to 500 characters...</textarea>
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Unlike most attributes, there is no "value" to assign. Therefore the attribute it passed in alone.
