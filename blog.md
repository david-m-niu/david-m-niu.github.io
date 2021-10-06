---
layout: default
---

### Up Close and Personal

A one-stop shop for my halfway organized thoughts. We'll probably be indundated with posts on measure theory for the rest of the semester, although I hope to get in some substantial material on NLP and music.

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

