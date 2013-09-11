---
layout: page
title: Hurray !!! my First publish
tagline: Supporting tagline
categories: [index,homepage]
---
{% include JB/setup %}


### About Me

I am saif,blah blah blah....

blah blah blah
    
## My Posts




<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


