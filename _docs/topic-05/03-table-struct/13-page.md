---
title: Tables in HTML
module: topic-05
permalink: /docs/topic-05/table-about/
redirect_from: /docs/topic-05/13-page.md
---

<style>
  table, th, td {
    border: 1px solid #ddd;
  }
</style>

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Tables are used to represent relationships and complex data, such as scores and stats, money markets, databases, etc.

In learning HTML, we can also use tables to organize less-complex (non-statistical) infomation. Tables can also break up linear information groups; for example, homweork step numbers, step details, and step images).

However, once we hit CSS, you should use stylesheets instead of HTML to organize text-based sets such as these. This is primarily because tables can be difficult for accessibility software to translate if done improperly.

The example on the following pages will show this situation, using a simple 2x2 set-up ("2 rows by 2 columns"):

<table style="width: 200px; margin: 40px auto;">
   <tr>
      <th></th>
      <th scope="col">Column A</th>
   </tr>
   <tr>
      <th scope="row">Row 1</th>
      <td>Cell A1</td>
   </tr>
</table>
