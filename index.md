---
layout: default
title: Your Site Title
description: A brief description of your site
---

# Welcome to My Site

This is the front page of my site, where I'll be sharing my latest blog posts and other updates.

## Latest Posts

{% for post in site.posts %}
- **{{ post.title }}**  
  *{{ post.date | date: "%B %-d, %Y" }}*  
  {{ post.excerpt }}  
  [Read More]({{ post.url }})
{% endfor %}
