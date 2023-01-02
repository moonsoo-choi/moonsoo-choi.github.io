---
layout: default
---

# `Currently working on following novellas & novellettes:`

## Bee Merry Co.
- TL;DR: can profit shape who you are?

## Meeting at the Dam

## The Second Lottery (Tribute to Shirley Jackson's Lottery)


# Drafts:

{% for post in site.tags["novellas"] %}
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

