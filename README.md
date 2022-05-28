# B100.dev

## To Do
- [ ] Blog 
- [ ] GPG
- [ ] Home 
- [ ] Portfolio 
- [ ] 



<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
