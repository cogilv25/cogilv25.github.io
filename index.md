---
layout: default
---

<h2><a href="portfolio">Portfolio</a></h2>

<h2><a href="blog">Blog</a></h2>

{% for post in site.posts %}

<div  style="margin-left: 10px">
<h3><a href="{{post.url}}">{{post.title}}</a></h3>
{{ post.excerpt }}
</div>

{% endfor %}

<h2><a href="other">Other</a></h2>