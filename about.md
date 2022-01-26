---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: default
---
{% include navigation.html %}

# About my website
This website was created on github with Jekyll and YAML.

YAML is yet another markdown language. Because nerds ~~think they'~~ are funny.

{{ site.description }}

This web page loaded at: {{ site.time }}

Here's a [quick link to another Carpentry lesson]({{page.lesson-example}}), called from a page-level variable.

[Go Home](.)

{% include footer.html %}
