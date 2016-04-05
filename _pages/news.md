---
layout: news
title: News &amp; Events
permalink: /news-events/
---
<h1>News &amp; Events</h1>

<h2>News</h2>
<ul class="post-list">
    {% for post in site.categories.news %}
      <li>

        <h3><a class="post-link" href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a></h3>

        <p class="post-meta">{{ post.date | date: "%b %Y" }}</p>
      </li>

    {% endfor %}
  </ul>
  <h2>Events</h2>
  <ul class="post-list">

     {% for post in site.categories.upcoming %}
      <li>

        <h3><a class="post-link" href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a></h3>

        <p class="post-meta">{{ post.date | date: "%b %Y" }}</p>
      </li>

    {% endfor %}
    </ul>
  <h2>Annoucements</h2>
  <ul class="post-list">

     {% for post in site.categories.announce %}
      <li>

        <h3><a class="post-link" href="{{ post.url | prepend: site.github.url }}">{{ post.title }}</a></h3>

        <p class="post-meta">{{ post.date | date: "%b %Y" }}</p>
      </li>

    {% endfor %}
  </ul>

