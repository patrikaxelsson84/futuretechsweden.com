---
layout: default
title: Articles
permalink: /articles/
---

# Articles

<section class="post-list">
  <h2>AI Gadgets &amp; Robots</h2>
  {% for post in site.categories["ai-gadgets"] %}
    <a class="post-card" href="{{ post.url | relative_url }}">
      <span class="post-card-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <span class="post-card-title">{{ post.title }}</span>
      {% if post.subtitle %}<span class="post-card-excerpt">{{ post.subtitle }}</span>{% endif %}
    </a>
  {% else %}
    <p>Nothing here yet.</p>
  {% endfor %}
</section>

<section class="post-list">
  <h2>Smart Home</h2>
  {% for post in site.categories["smart-home"] %}
    <a class="post-card" href="{{ post.url | relative_url }}">
      <span class="post-card-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <span class="post-card-title">{{ post.title }}</span>
      {% if post.subtitle %}<span class="post-card-excerpt">{{ post.subtitle }}</span>{% endif %}
    </a>
  {% else %}
    <p>Nothing here yet.</p>
  {% endfor %}
</section>

<section class="post-list">
  <h2>Wearables</h2>
  {% for post in site.categories["wearables"] %}
    <a class="post-card" href="{{ post.url | relative_url }}">
      <span class="post-card-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <span class="post-card-title">{{ post.title }}</span>
      {% if post.subtitle %}<span class="post-card-excerpt">{{ post.subtitle }}</span>{% endif %}
    </a>
  {% else %}
    <p>Nothing here yet.</p>
  {% endfor %}
</section>

<section class="post-list">
  <h2>Guides</h2>
  {% for post in site.categories["guides"] %}
    <a class="post-card" href="{{ post.url | relative_url }}">
      <span class="post-card-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <span class="post-card-title">{{ post.title }}</span>
      {% if post.subtitle %}<span class="post-card-excerpt">{{ post.subtitle }}</span>{% endif %}
    </a>
  {% else %}
    <p>Nothing here yet.</p>
  {% endfor %}
</section>
