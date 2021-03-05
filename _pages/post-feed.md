---
layout: single
title: "All Details in One Page"
permalink: /post-feed/
---





<div class="posts">

  {% for post in site.posts  %}

<hr>
<hr style="border-top: dotted 5px;" />


  <div class="post">
    <h1 class="post-title">
      <a href="{{ site.baseurl }}{{ post.url }}">
        {{ post.title }}
      </a>
    </h1>

    <span class="post-date">{{ post.date | date_to_string }}</span>

    {{ post.content }}
  </div>
  {% endfor %}
</div>