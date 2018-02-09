---
layout: page
title: posts
category: tech
foo: "bar"
---


<h1>All the posts...</h1>

<hr>
<br>

{% for post in site.posts %}

<h1>{{post.title}}</h1>
<h4>{{post.date}} | {{ post.categories }}<h4>
{{post.content}}
<hr>
<br>

{% endfor %}
