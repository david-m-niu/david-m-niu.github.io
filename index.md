## Why Is This So Hard?

Hi, I'm David Niu, and this is my landing page. Nothing to see here, if you can read this you're too close, *et cetera, ad ad infinitum, ad nauseum*.

### Blog

Contrary to popular belief, I do learn things occasionally; when it's particularly noteworthy, I blog to celebrate. You can read my latest posts below.

<ul>
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
