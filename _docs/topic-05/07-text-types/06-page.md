---
title: Columns and Rows
module: topic-05
permalink: /docs/topic-05/text-cols-rows/
redirect_from: /docs/topic-05/07-text-types/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

You can specify the number of `cols` and `rows` through the appropriate attributes. This changes the size of the displayed element, as well as how text will look when typed.

- `cols` is the width of the textarea in character widths (i.e. this is the number of characters that will fit from left to right).
- `rows` is the number of visible lines.


<div id="code-heading">HTML</div>
```html
<p>
  Comments or Concerns:
  <textarea name="comments" id="test-textarea" cols="20" rows="4">Enter up to 500 characters...</textarea>
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
              <input type="text" name="name" id="test-date" maxlength="4" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 2.6em;">Net ID:</span>
              <input type="text" name="name" id="test-text" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 1.2em;">Password:</span>
              <input type="password" name="password" id="test-password" maxlength="15"/>
            </p>
            <p style="font-size: large;">
              <span>Comments or Concerns:</span>
              <textarea name="comments" id="test-textarea" cols="20" rows="4" style="width:100%; border-color: #D8D8D8 !important; color: #777; font-size: medium">Enter up to 500 characters...</textarea>
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Typically, and as is the case with many size parameters that you can set in HTML, you should override these parameters with CSS.
