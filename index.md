---
layout: default
permalink: /
image:
---

<div id="instagram" class="">
{% include device.html %}
</div>

<div id="subscribe" class="wrap">
{% include subscribe.html %}
<div>

<div id="content" class="main">
  <div class="wrap">
    <h1 id="posts">Latest Posts</h1>
  <div class="tiles">
    {% for post in site.posts %}
        {% include post-grid.html %}
        {% endfor %}
  </div><!-- /.tiles -->
  </div>
</div>
