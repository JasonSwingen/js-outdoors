---
layout: default
permalink: /
image:
---

<div id="content" class="main">

  <div class="page-lead" style="background-image:url(/images/2017-king-salmon.jpg)">
      <div class="page-lead-content">
        <div class="page-lead-title">
          <!-- <img src="images/JS_OUTDOORS_long_logo.jpg" alt=""> -->
          <p>Welcome to JS-Outdoors. Hunting and Fishing stories written for and by the Midwestern Outdoorsman. If you have a passion for the outdoors too, then check out some of my most recent adventures below!</p>
          <a class="btn" target="_blank" href="#instagram">Follow Along</a>
          <a class="btn btn-accent" href="#posts">View Posts</a>
        </div>
      </div>
  </div>

<div id="main" role="main" id="posts">
<div class="wrap">
  <h1><a href="{{ domain }}/blog.html">Recent Posts</a></h1>
    <div class="tiles">
      {% for post in site.posts limit:12 %}
          {% include post-grid.html %}
      {% endfor %}
    </div>
</div>
</div>

<div class="section">
  <div class="wide">
      {% include youtube-grid.html %}
  </div>
</div>

<div id="instagram" class="">
  {% include device.html %}
</div>

<div class="section">
  {% include subscribe.html %}
</div>

</div>
