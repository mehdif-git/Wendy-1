---
title : Wendy-1, my first synth
---
{% include README.md %}

# Blogposts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl | append: post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
