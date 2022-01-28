---
layout: default
---

## Blog Posts
{% for post in site.blogposts %}
- {{ post.date | date_to_string }}:[{{ post.title }}]  
({{ post.url }}){% endfor %}  
