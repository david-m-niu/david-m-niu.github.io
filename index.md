## Why Is This So Hard?

Hi, I'm David Niu, and this is my landing page.

### Blog

Contrary to popular belief, I do learn things occasionally, and when it's particularly noteworthy, I write about it here.

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
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
