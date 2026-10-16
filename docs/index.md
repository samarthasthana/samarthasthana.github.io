---
layout: default
title: Posts
---

# Agents at Home

Notes from building self-hosted AI agents with Hermes Agent, local models like Qwen, and cloud models like Claude. What worked, what broke, and what it cost.

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="meta">{{ post.date | date: "%B %-d, %Y" }}</span>
    {% if post.description %}<p>{{ post.description }}</p>{% endif %}
  </li>
{% endfor %}
</ul>
