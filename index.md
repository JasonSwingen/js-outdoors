---
layout: default
permalink: /
image:
---

<div id="content" class="main">

  {% for post in site.posts  limit:1%}
  <div class="page-lead" style="background-image:url({{ site.url }}/images/{{ post.image.teaser }})">
    <a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}" class="post-teaser">
      <div class="page-lead-content">
        <h1 class="page-lead-title">{{ post.title }}</h1>
      </div>
    </a>
  {% endfor %}
  </div>

  <div class="wrap">
    <h1 id="posts">Latest <a href="/blog.html">Posts</a></h1>
    <div class="tiles">
      {% for post in site.posts offset:1 limit:8%}
          {% include post-grid.html %}
          {% endfor %}
    </div><!-- /.tiles -->
  </div>

  {% include snapwidget.html %}

  {% include subscribe.html %}
