---
title: Meta
module: topic-04
permalink: /docs/topic-04/head-meta/
redirect_from: /docs/topic-04/15-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

The **META element** lives inside the head element and contains information about that webpage.
It is not visible to users but fulfills a number of purposes such as telling search engines about your page, who created it, and whether or not it is time-sensitive.

The meta element is an _empty element_, like the upcoming link element. The most common attributes are 'name' and 'content'. These attributes are often used together and specify the properties of the entire page:

1. The value of the name attribute is the property you are setting.
2. The value of the content attribute is the value that you want to give to this property.

For example, on the second meta line below, the name attribute indicates an intention to specify a description for the page. The content attribute is where this description is actually specified.
The value of the name attribute can be anything you want it to be.

We will look at the Meta element more later. For the time being however, you should include the following meta elements in your pages:

- _charset_ - This define the character set to use for page display. To display an HTML page correctly, a web browser must know which character set (character encoding) to use. **UTF-8** (Unicode) covers almost all of the characters and symbols in the world. This includes the original ASCII standard that covers most of the character symbols you use.
- _Description_ - This contains a description of the page. This description is commonly used by search engines to understand what the page is about. As such, it should be less than 155 characters.
- _Author_ - This defines the author of the webpage.

<span class="label label-info">NOTE:</span> The _charset_ attribute is usually the first element in the head.

<div id="code-heading">HTML</div>
```html
<!DOCTYPE html>
<html>
  <head>

    <!-- Define the character set used: -->
    <meta charset="UTF-8">

    <!-- Provide a description of your page: -->
    <meta name="description" content="Head Elements in HTML">

    <!-- Provide the author information for the page: -->
    <meta name="author" content="Justine Evans">

  </head>

</html>
```
