---
title: Tooltips
tags: [formatting]
keywords: popovers, tooltips, user interface text, glossaries, definitions
last_updated: July 3, 2016
summary: "You can add tooltips to any word, such as an acronym or specialized term. Tooltips work well for glossary definitions, because you don't have to keep repeating the definition, nor do you assume the reader already knows the word's meaning."
sidebar: mydoc_sidebar
permalink: mydoc_adding_tooltips.html
folder: mydoc
---

## Creating 


{% raw %}
```html
<a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.jekyll_platform}}">Jekyll</a> is my favorite tool for building websites.
```
{% endraw %}

This renders to the following:

<a href="#" data-toggle="tooltip" data-original-title="{{site.data.glossary.jekyll_platform}}">Jekyll</a> is my favorite tool for building websites.

{% include links.html %}
