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
        <div class="page-lead-title">
          <h1>{{ post.title }}</h1>
        </div>
      </div>
    </a>
  {% endfor %}
  </div>

<div class="section">
  <div class="wide">
    <div class="wrap">
      <div class="text">
        <h1><a href="/fishing.html">Fishing</a></h1>
      </div>
      <div class="">
        <div class="">
        {% for post in site.tags.fishing limit:4 %}
            {% include post-grid.html %}
        {% endfor %}
        </div>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <div class="wide">
    <div class="wrap">
      <div class="text">
        <h1><a href="/hunting.html">Hunting</a></h1>
      </div>
      <div class="">
        <div class="">
        {% for post in site.tags.hunting limit:4 %}
            {% include post-grid.html %}
        {% endfor %}
        </div>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <div class="wide">
    <div class="wrap">
      <div class="text">
        <h1><a href="/reviews.html">Reviews</a></h1>
      </div>
      <div class="">
        <div class="">
        {% for post in site.tags.reviews limit:4 %}
            {% include post-grid.html %}
        {% endfor %}
        </div>
      </div>
    </div>
  </div>
</div>

<div class="section">
  {% include snapwidget.html %}
</div>

<div class="section">
  {% include subscribe.html %}
</div>

</div>
