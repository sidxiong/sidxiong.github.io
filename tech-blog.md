---
layout: layout
title: Technology Blog
---

<section class="content">
# Technology Blog

  <ul class="listing">
    {% for post in site.categories.tech %}
      <li>
        <span>{{ post.date | date: "%B %e, %Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>

</section>
