---
layout: post
title: Welcome
---

Welcome to my blog.


### RECENT POSTS
<div>
    {% assign posts_list = site.posts %}
    {% for node in posts_list %}
      {% if node.title != null and node.title != 'Welcome'%}
        
          <a class="" href="{{ node.url }}">{{ node.title }}</a>
        
      {% endif %}
    {% endfor %}
</div>