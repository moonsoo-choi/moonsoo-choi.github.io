---
layout: default
---

## Being vs. Doing
- An attempt to explain why excessive <em>doing</em> is a heresy (but why excessive <em>being</em> is not)

{% for post in site.tags["being vs doing"] %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.content }}
  </article>
{% endfor %}

