---
layout: layout
title: Life
---

<section class="content">
# Life

  <ul class="listing">
    {% for post in site.categories.life %}
      <li>
        <span>{{ post.date | date: "%B %e, %Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>

</section>
