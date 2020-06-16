---
layout: page
title: Welcome
tagline: Supporting tagline
---
{% include JB/setup %}

About this Portfolio

This page is intended to be a portfolio of my previous work and a collection of posts of articles I found interesting. 

For more general information about myself, either click about or visit my [main  webpage](http://www.carlosandrade.co)

## Pages

Browse pages for a list of complete previous work. 
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


