---
layout: default
title: Articles
permalink: /articles/
---

# Articles

<section class="post-list">
  <h2>AI Gadgets &amp; Robots</h2>
  <div class="post-grid">
    {% for post in site.categories["ai-gadgets"] %}
      {% include post-card.html post=post %}
    {% else %}
      <p>Nothing here yet.</p>
    {% endfor %}
  </div>
</section>

<section class="post-list">
  <h2>Smart Home</h2>
  <div class="post-grid">
    {% for post in site.categories["smart-home"] %}
      {% include post-card.html post=post %}
    {% else %}
      <p>Nothing here yet.</p>
    {% endfor %}
  </div>
</section>

<section class="post-list">
  <h2>Wearables</h2>
  <div class="post-grid">
    {% for post in site.categories["wearables"] %}
      {% include post-card.html post=post %}
    {% else %}
      <p>Nothing here yet.</p>
    {% endfor %}
  </div>
</section>

<section class="post-list">
  <h2>Guides</h2>
  <div class="post-grid">
    {% for post in site.categories["guides"] %}
      {% include post-card.html post=post %}
    {% else %}
      <p>Nothing here yet.</p>
    {% endfor %}
  </div>
</section>
