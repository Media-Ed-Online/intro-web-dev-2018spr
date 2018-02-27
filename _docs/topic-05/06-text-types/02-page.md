---
title: Plain Text
module: topic-05
permalink: /docs/topic-05/text-plain/
redirect_from: /docs/topic-05/06-text-types/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

This following code demonstrates how to create an input element of `type="text"`. Please notice the use of the `<p>...</p>` element to display information text in front of the text box.


<div id="code-heading">HTML</div>
```html
<p>
  Net ID:
  <input type="text" name="name" id="test-text" />
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
              <input type="text" name="name" id="test-date" />
            </p>
            <p style="font-size: large;">
              <span style="margin-right: 2.6em;">Net ID:</span>
              <input type="text" name="name" id="test-text" />
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Technically, you can omit the "type" from the input element if you want a text box. But good style dictates that you should be explicit in your code so as to prevent errors. So don't.
