---
title: Clarity and Structure with ids
module: topic-06
permalink: /docs/topic-06/id-clarity/
redirect_from: /docs/topic-06/01-id-att/01-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

There are a number of attributes that are valid for every element. The first that we will discuss is technically called the "Global Attribute,"
however, we will refer to it as the **'ID' attribute**.

<div class="container-row">
  <img src="../img/legos-ids.png" alt="stacked building blocks with different id names" title="Each block has a unique name!" style="float: right; width: 300px; margin-top: 0;" />

  <p>Following from the idea of identification labels, the 'ID' attribute takes as its value a string, which should be a "unique identifier" to that specific element; as in, <i>the ID given to one element should be different from every other element's ID on a page</i>.</p>

  <p>To declare the 'ID' attribute of an element, use the standard <code>key="value"</code> syntax for HTML elements.</p>
</div>


<div id="code-heading">HTML</div>
```html
<div id="a-unique-id">

<div id="another-unique-id">
```

You should get in the habit of adding ID attributes to any important HTML elements or elements that you may want to style independently. The ID attribute is one of the ways that we will select elements via CSS to dictate the style and look of our webpages.
