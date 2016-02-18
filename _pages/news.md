---
layout: news
title: News
permalink: /news/index.htm
category: news
---
<h1>News</h1>

<ul class="post-list">
    {% for post in site.categories.news %}
      <li>
   

          <h4></h4>
          <a class="post-link" style="font-size:14pt;" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          
        
        <p class="post-meta">{{ post.date | date: "%b %Y" }}</p>
      </li>
      
    {% endfor %}
  </ul>
   
