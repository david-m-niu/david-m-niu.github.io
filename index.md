## Why Is This So Hard?

Hi, I'm David Niu; I'm a student at UNC Chapel Hill double majoring in math and CS while minoring in music. This is my landing page&mdash;nothing to see here, if you can read this you're too close, *et cetera, ad ad infinitum, ad nauseum*.

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
