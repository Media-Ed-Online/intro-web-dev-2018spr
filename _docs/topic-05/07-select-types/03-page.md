---
title: The Checkbox Element
module: topic-05
permalink: /docs/topic-05/select-checkbox/
redirect_from: /docs/topic-05/07-select-types/03-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

**Checkboxes** (`type="checkbox"`) allow users to select (or deselect) **zero, one,** or **more** options.


### name (Required)

When grouping checkboxes, as with radio buttons, the `name=""` should be the same for each element option.


### value (Required)

Likewise, the `value=""` should be unique to each element.


### checked (Optional)

As with radio buttons, you can use the `checked` attrubite to pre-select checkboxes.


<div id="code-heading">HTML</div>
```html
<p>Services Utilized:</p>
  <input type="checkbox" name="service" value="lab" /> Computer Lab
  <br />
  <input type="checkbox" name="service" value="library" /> Library
  <br />
  <input type="checkbox" name="service" value="online" checked /> Moodle / Online Resources
  <br />
  <input type="checkbox" name="service" value="recreation" /> Gym or Rec Center
```

<div class="row" style="margin-top: -30px;">
  <div class="col-lg-12">
    <div class="bs-component">
      <div class="panel panel-success">
        <div class="panel-heading">
          <h4 style="text-transform: uppercase; margin: inherit;">
            <i class="fa fa-check-circle" aria-hidden="true" style="margin-right: 10px"></i>
            Please Select:
          </h4>
        </div>
          <div class="panel-body">
            <p style="font-size: large;">Registration Type:</p>
              <input type="radio" name="reg" value="campus" /> On Campus
              <br />
              <input type="radio" name="reg" value="distance" /> Distance-Only

            <p style="font-size: large; margin-top: 1.5em;">Admission Level:</p>
              <input type="radio" name="level" value="nondeg" /> Nondegree
              <br />
              <input type="radio" name="level" value="undergrad" checked /> Undergraduate
              <br />
              <input type="radio" name="level" value="grad" /> Graduate
              <br />
              <input type="radio" name="level" value="other" /> Other: <input type="text" name="other" id="level-other-text" style="margin-left: 1em;" size="30" />

            <p style="font-size: large; margin-top: 1.5em;">Services Utilized</p>
              <input type="checkbox" name="service" value="lab" /> Computer Lab
              <br />
              <input type="checkbox" name="service" value="library" /> Library
              <br />
              <input type="checkbox" name="service" value="online" checked /> Moodle / Online Resources
              <br />
              <input type="checkbox" name="service" value="recreation" /> Gym or Rec Center
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Displayed text should appear AFTER each checkbox element.
