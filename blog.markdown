---
layout: default
title: Blog
permalink: /blog/
---
<ul>
    {% for post in site.posts %}
        <li>
        <a href="{{ post.url }}">{{ post.title }}</a> {{ post.date | date: "%b %dth, 20%y" }}
       
        <p>{{ post.excerpt }}</p>
    
        
        </li>
    {% endfor %}
</ul>