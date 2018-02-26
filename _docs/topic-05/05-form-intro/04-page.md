---
title: Method
module: topic-05
permalink: /docs/topic-05/form-method/
redirect_from: /docs/topic-05/05-form-intro/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%">
      <span class="sr-only">75% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><form action="#"</span> <span style="color: #79AF33; font-weight: bold;">method="..."</span> <span style="color: #999">id="..." class="..."> ... </form></span></p>
  </div>
</div>


Forms can be sent using one of two methods; '`get`' or '`post`'.

With the '`get`' method, values are added to the end of the specified action URL.

This methods is ideal for searches, or for _retrieving_ data from a server (as opposed to sending data that will be stored in a database).

With the '`post`' method, values are sent in what are known as 'HTTP headers'. As a rule of thumb, use the '`post`' method when;

- users are uploading a file.
- the data will be very long
- the data is sensitive (ie. contains passwords)
- The data is intended to alter or access a database on the server.
