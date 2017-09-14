---
layout: page
title: Blog
permalink: /blog/
---

<div class="container">
<h1>Electronics </h1>
<ul>

    {% for post in site.categories.electronics %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>

<h1>Software </h1>
<ul>
  {% for post in site.categories.software %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
</div>

[jekyll-organization]: https://github.com/jekyll
