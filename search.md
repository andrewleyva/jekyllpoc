---
layout: page
title: search
---

**List of Posts:**



{% for post in site.posts %}
 
 {% if post.title %}
   <a href="/{{site.baseurl}}{{post.url}}">{{ post.title }}</a>({{site.baseurl}}{{post.url}})
 {% endif %}

{% endfor %}
