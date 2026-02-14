---
section_id: news
section_class: news-section
order: 3
---

## News

Stay updated with our newest arrivals, events, and menu items.

<div class="news-grid">
{% for post in site.posts limit:3 %}
  <article class="news-item">
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
    <a href="{{ post.url | relative_url }}" class="read-more">Read more →</a>
  </article>
{% endfor %}
</div>
