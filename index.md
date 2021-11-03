---
layout: default
---

## Why Is This So Hard?

This is my landing page&mdash;nothing to see here, if you can read this you're too close, *et cetera, ad infinitum, ad nauseum*.

### About

I'm a sophomore at UNC Chapel Hill double majoring in math and CS while minoring in music. My academic interests are in mathematical analysis and deep learning, although I spend a disproportionately large amount of time finding the willpower to practice piano. 

### Blog

Contrary to popular belief, I do learn things occasionally; when it's particularly noteworthy, I blog to celebrate. You can read my latest posts below, and if they aren't mindnumbing enough, feel free to satiate your perverted desires with the rest of my [entries](blog.md).

<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

### [Notes | Where Is My Intuition?](notes.md)

Sometimes, things are painfully obvious, and I wonder how I ever could not have understood this or that concept. Then, I forget everything and the cycle repeats. Until now, that is.
