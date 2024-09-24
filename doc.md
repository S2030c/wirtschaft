---
layout: default
---

<p>Texte zum Themenbereich</p>

<div class="posts">
  {% for post in site.categories.doc %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Lesen</a>
    </article>
  {% endfor %}
</div>
