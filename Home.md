---
layout: page
title: "Home"
permalink: /HOME/
---

# B100.dev

## To Do
- [ ] Blog 
- [ ] GPG
- [ ] Home 
- [ ] Portfolio 
- [ ] 







## My Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
