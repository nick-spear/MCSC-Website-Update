---
layout: news
title: Archive
permalink: /news/archive.html
category: news
---
<h1>Archived News</h1>

<ul class="post-list">
    {% for post in site.categories.archive %}
      <li>
   

          <h4></h4>
          <a class="post-link" style="font-size:14pt;" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          
        
        <p class="post-meta">{{ post.date | date: "%b %Y" }}</p>
      </li>
      
    {% endfor %}
  </ul>
   
