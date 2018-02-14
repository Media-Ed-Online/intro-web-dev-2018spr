---
title: Namining IDs
module: topic-04
permalink: /docs/topic-04/naming-ids/
redirect_from: /docs/topic-04/51-page.md
---

<img src="./../../../img/arrow-divider.svg" style="width: 75px; border: none; margin: 0px 0 20px 0" />

<span class="label label-info">NOTE:</span> IDs should be treated like variables in other languages, with regards to the naming conventions.

1. The value should be surrounded by double quotes (i.e. `name=“value”`).
2. For IDs, the value should start with a lowercase letter (i.e. a-z).
3. IDs can contain lowercase letters, uppercase letters, numbers, and some special characters (although the latter should typically be avoided).
4. ID’s should be explicit and clear with regard to what they are referencing.(i.e. “firstSection”, “aside-paragraph”, “hero\_image”).
5. Try to avoid abbreviations for words in IDs (i.e. “first-paragraph” over “firPara”).
6. When creating IDs that are multiple words, you should follow one of three conventions. Additionally, you should follow this convention in _all of your code_, so that there is consistency to your work and style.
	-  _camelCase_ - [Camel Case](https://en.wikipedia.org/wiki/Camel_case) pushes multiple words together into a single word, capitalizing the first letter of every word, except for the first (i.e. `name="exampleValueHere"`)
	- _hyphen-separated_ - Each word is separated by a hyphen ( `-` ) character.
	- _underscore\_separated_ - Each word is separated with an underscore ( `_` ) character.


### Why?

Hrefs _reference_ URLs, so just like our discussion from <a href="{{ site.url }}/docs/topic-02/file-naming-quiz/" target="_blank">Topic 02</a>, you must follow naming standards to locate even portions of a page.

For example, did you notice how the URL changed in your address bar when you clicked one of the links on the previous page?
	![Image of address bar changes](../img/href-id-url-change.jpg)
