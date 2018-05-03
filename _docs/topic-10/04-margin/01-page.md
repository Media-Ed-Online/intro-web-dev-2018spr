---
title: Adding Separation
module: topic-10
permalink: /docs/topic-10/margin-intro/
redirect_from: /docs/topic-10/04-margin/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Looking back to our box model, we can see that the **margin** is the space between the box/element and other elements or the edge of the parent element.

<style>
  .parent-container {
      font-family: sans-serif;
      font-style: italic;
      font-size: 32px;
      text-align: center;
      padding: 0.5em;
      width: 98%;
      /*border: 1px solid black;*/
      margin-top: 2em;
  }
  .margin {
      font-size: 18px;
      font-style: normal;
      font-family: sans-serif;
      border: 2px dashed #4e4e4e;
      background-color: #a7a7a7;
      padding: 1.5em;
      padding-top: 0em;
  }
  .border {
      background-color: #373E42;
      color: #fff;
      padding: 1.5em;
      padding-top: 0em;
  }
  .padding {
      background-color: #a7a7a7;
      color: #000;
      padding: 1.5em;
      padding-top: 0em;
  }
  .example-content {
      background-color: #79AF33;
      color: #fff;
      border: 2px dashed #d5d5d5;
      padding: 0em;
      /*padding-top: 0.5em;*/
      font-size: 2.5em;
  }
</style>
<div class="parent-container">
  <a href="https://www.w3schools.com/css/css_boxmodel.asp">The Box Model</a>
  <div class="margin">
      <img src="../img/hand-point-right.png" style="width: 50px; border: none; display: inline;" /> Margin <img src="../img/hand-point-left.png" style="width: 50px; border: none; display: inline;" />
      <div class="border">
          Border
          <div class="padding">
              Padding
              <div class="example-content">
                  The Content!
              </div>
          </div>
      </div>
    </div>
</div>

As with padding, margin accepts both absolute and relative size units.
