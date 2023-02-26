# work in progress
kumiko is learning analysis
layout: default
---

{% for post in site.posts %}
  ## [{{ post.title }}]({{ post.url }})

  *{{ post.date | date_to_string }}*

  {{ post.excerpt }}
{% endfor %}
