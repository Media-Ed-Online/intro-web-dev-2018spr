---
title: Labels and IDs
module: topic-05
permalink: /docs/topic-05/form-labels-ids/
redirect_from: /docs/topic-05/09-form-mgmnt/02-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

Each form control should have its own **label element**. _This makes the form accessible to vision impaired users._

As a rule of thumb, labels should be placed 'above or to the left' of the input area for text, select boxes, and file uploads (this is the same idea presented earlier with `<p>...</p>`).

Labels should be placed to the right of individual checkboxes and radio buttons. Labels can be applied by wrapping them around both the text description and the form input.

Labels can also be included by using the `for=""` attribute. The value for this attribute should be the **id** assigned to each form element.

<span class="label label-info">NOTE:</span> This also expands the clickable area available to the user.


<div class="codepen-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="GMOobr" data-default-tab="html,result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Topic-05: Labelling Form Elements, Pt. 1" class="codepen"></p>
</div>
