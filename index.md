---
title: Welcome to my blog
---
hello this is the blog of mohammad turani an aspiring computer scientest,
 below you will see the table of content which will be updated regularly with my notes, projects, or books that i read

Table of content:
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
