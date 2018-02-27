---
title: Password
module: topic-05
permalink: /docs/topic-05/text-password/
redirect_from: /docs/topic-05/07-text-types/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The `type="password"` for input elements creates a "password input box".

This attribute creates a single line text entry field where the characters are hidden with `*`s.


<div id="code-heading">HTML</div>
```html
<p>
  Password:
  <input type="password" name="password" id="test-password" />
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
            <p style="font-size: large;">
              <span style="margin-right: 1.2em;">Password:</span>
              <input type="password" name="password" id="test-password" maxlength="15"/>
            </p>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> You would never use this type of field to send sensitive data such as SSN's. For such situations, a site should create a web socket or use an Secure Socket Layer (SSL) connection with a server to guarantee secure delivery of data.
