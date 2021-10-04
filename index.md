## Why Is This So Hard?

Hi, I'm David Niu, and this is my landing page. Noting to see here, if you can read this you're too close, *et cetera, ad ad infinitum, ad nauseum*.

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

<!---
```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text
[Link](url) and ![Image](src)
```
--->
