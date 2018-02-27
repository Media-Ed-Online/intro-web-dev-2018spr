---
title: The &lt;input&gt; Element
module: topic-05
permalink: /docs/topic-05/input-element/
redirect_from: /docs/topic-05/06-form-input/06-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

## Altogether

An input element is a combination of type, name, and identification. The following code shows an "input" element, wrapped in a "form" element, along with the three _required_ attributes.


<div id="code-heading">HTML</div>
```html
<form action="http://www.example.com/login.php" method="post" id="sign-in" class="basic-forms">
    <input type="text" name="username" id="username_input" />
</form>
```


The `<form>` is improving with the addition of `<input>` elements. Specifing **input types** is where the real magic happens.
