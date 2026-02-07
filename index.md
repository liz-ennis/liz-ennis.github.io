---
layout: page
---

Welcome.

This is a place for writing, reflections, and small moments worth keeping.

## Posts

<!-- POSTS_START -->

- 2026-02-07 — [One more test](posts/2026-02-07-one-more-test.md)

<!-- POSTS_END -->

<ul>
{% for post in site.posts %}
  <li>
    {{ post.date | date: "%Y-%m-%d" }} —
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

(V13)
