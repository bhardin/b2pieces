---
layout: page
title: Board2Pieces Podcast
tagline: Supporting111 tagline
---
{% include JB/setup %}
    
<ul class="posts">
  {% for post in site.posts %}
  <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>
  <h3><small>{{ post.date | date_to_string }}</small></h3>

  <p>{{ post.content }}</p>
  <a href="{{ post.podcast_url }}">Download This Episode!</a><br/><br/>

  {% endfor %}
</ul>


