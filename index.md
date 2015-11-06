---
title: The Digital Platform
---
Welcome to the Digital Platform for Your Life!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% include footer.md %}
