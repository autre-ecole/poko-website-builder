---
translationKey: articles-archive
status: published
name: Articles (archive)
---

# Articles (archive)

<div class="articles-list grid-fluid">
{%- for post in collections.articles -%}
  <article class="article-card breakout-clickable">
    <h3 class="h4"><a href="{{ post.url }}">{{ post.data.title }}</a></h3>
    <div class="article-meta">
      <time datetime="{{ post.date | dateToSlug }}" class="article-date">{{ post.date | toLocaleString(lang, { year: "numeric", month: "long", day: "numeric" }) }}</time>
      {% if post.data.author %}<span class="article-author">par {{ post.data.author }}</span>{% endif %}
    </div>
    {% if post.data.description %}
    <p class="article-description">{{ post.data.description }}</p>
    {% endif %}
  </article>
{%- endfor -%}
</div>

{% partial "styles-articles-list.md" %}
