---
title: Radio Buttons
module: topic-05
permalink: /docs/topic-05/select-radio/
redirect_from: /docs/topic-05/07-select-types/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

**Radio Buttons** (`type="radio"`) allow users to select **one** item.

Notice in the code example below, that this element, like the text box, will likely be placed in a `<p>...</p>`. This makes it easy to add information or "choice" text around the elements.


### name (Required)

Radio buttons need to be grouped together. This tells the browser that only "one of the choices" of this group can be selected. To group radio button elements together the developer provides the same `name=""` attribute value for each possible choice. As with all elements, this name attribute will be sent along with the returned data.


### value (Required)

Unlike text boxes, where the user enters unique data, radio buttons provide discrete options/data. To set the data that might be returned from this element, use the `value=""` attribute.


### checked (Optional)

The `checked="checked"` attribute can be used with one of the radio button elements to 'pre-select' an option that will be displayed when the page loads.


<div id="code-heading">HTML</div>
```html
<p>Admit Type:</p>
  <input type="radio" name="level" value="nondeg" /> Nondegree
  <br />
  <input type="radio" name="level" value="undergrad" checked /> Undergraduate
  <br />
  <input type="radio" name="level" value="grad" /> Graduate
  <br />
  <input type="radio" name="level" value="other" /> Other
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
              <input type="radio" name="level" value="undergrad" checked="checked" /> Undergraduate
              <br />
              <input type="radio" name="level" value="grad" /> Graduate
              <br />
              <input type="radio" name="level" value="other" /> Other: <input type="text" name="other" id="level-other-text" style="margin-left: 1em;" size="30" />
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> A radio button set cannot be “deselected.”
