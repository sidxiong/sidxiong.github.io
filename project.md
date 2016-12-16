---
layout: layout
title: CV
---

<section class="content">
# Projects

  <ul class="listing">
    {% for post in site.categories.projects %}
      <li>
        <span>{{ post.date | date: "%B %e, %Y" }}</span>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
      </li>
    {% endfor %}
  </ul>

</section>
