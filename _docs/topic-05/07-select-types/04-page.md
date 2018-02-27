---
title: The Select Box (AKA Dropdown Select)
module: topic-05
permalink: /docs/topic-05/select-dropdown/
redirect_from: /docs/topic-05/07-select-types/04-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

A **select box** allows a user to select one option from a dropdown list.

Unlike the other form elements we have been looking at, this element has its own name and uses opening and closing tags: `<select>...</select>`.

Dropdown lists are very similar to radio buttons, however these are more appropriate when a large amount of selections is possible (i.e. "select a state").



### option (Required)

The **option element** (`<option>...</option>`) is used within select elements to indicate each possible option. Any text between the option tags will be displayed in the dropdown box.


### value (Required)

As with other form types, the `value=""` attribute should be unique for each option element. This will be sent back with the select elements name attribute.


### selected (Optional)

The `selected` attribute can be used to pre-select an option. If this attribute is omitted then the first option will be pre-selected.


<div id="code-heading">HTML</div>
```html
<p>Home State (US Residents):</p>
  <select name="home_state">
    <option value="AL">Alabama</option>
    <option value="AK">Alaska</option>
    <option value="AZ">Arizona</option>
    <option value="AR">Arkansas</option>
    <option value="CA">California</option>
    <option value="CO" selected>Colorado</option>
    <option value="CT">Connecticut</option>
    <!-- Continued... -->
  </select>
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

            <p style="font-size: large; margin-top: 1.5em;">Home State (US Residents):</p>
              <select name="home_state">
                <option value="AL">Alabama</option>
                <option value="AK">Alaska</option>
                <option value="AZ">Arizona</option>
                <option value="AR">Arkansas</option>
                <option value="CA">California</option>
                <option value="CO" selected>Colorado</option>
                <option value="CT">Connecticut</option>
                <option value="DE">Delaware</option>
                <option value="DC">District Of Columbia</option>
                <option value="FL">Florida</option>
                <option value="GA">Georgia</option>
                <option value="HI">Hawaii</option>
                <option value="ID">Idaho</option>
                <option value="IL">Illinois</option>
                <option value="IN">Indiana</option>
                <option value="IA">Iowa</option>
                <option value="KS">Kansas</option>
                <option value="KY">Kentucky</option>
                <option value="LA">Louisiana</option>
                <option value="ME">Maine</option>
                <option value="MD">Maryland</option>
                <option value="MA">Massachusetts</option>
                <option value="MI">Michigan</option>
                <option value="MN">Minnesota</option>
                <option value="MS">Mississippi</option>
                <option value="MO">Missouri</option>
                <option value="MT">Montana</option>
                <option value="NE">Nebraska</option>
                <option value="NV">Nevada</option>
                <option value="NH">New Hampshire</option>
                <option value="NJ">New Jersey</option>
                <option value="NM">New Mexico</option>
                <option value="NY">New York</option>
                <option value="NC">North Carolina</option>
                <option value="ND">North Dakota</option>
                <option value="OH">Ohio</option>
                <option value="OK">Oklahoma</option>
                <option value="OR">Oregon</option>
                <option value="PA">Pennsylvania</option>
                <option value="RI">Rhode Island</option>
                <option value="SC">South Carolina</option>
                <option value="SD">South Dakota</option>
                <option value="TN">Tennessee</option>
                <option value="TX">Texas</option>
                <option value="UT">Utah</option>
                <option value="VT">Vermont</option>
                <option value="VA">Virginia</option>
                <option value="WA">Washington</option>
                <option value="WV">West Virginia</option>
                <option value="WI">Wisconsin</option>
                <option value="WY">Wyoming</option>
              </select>
          </div>
      </div>
    </div>
  </div>
</div>


<span class="label label-info">NOTE:</span> Displayed text should appear AFTER each checkbox element.
