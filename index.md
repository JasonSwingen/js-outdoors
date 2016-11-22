---
layout: default
permalink: /
image:
---

<div class="page-lead" style="background-image:url(/images/2015_MT_Hunt_11.jpg)">
    <div class="wrap page-lead-content">
        <!-- <h1>JS-OUTDOORS</h1> -->
        <h2>Welcome to JS-Outdoors. My name is Jason Swingen and I am a Multi-species angler, big-game hunter, and avid outdoorsman living in Minnesota. Sign up to stay informed of new fishing and hunting information, as well as stories, reports, and reviews!</h2>
        <!-- <a href="/report/fishing-report" class="btn">Fishing Reports</a>
        &nbsp;
        <a href="/blog.html" class="btn-accent">Latest Posts</a> -->
          {% include subscribe.html %}
        {% include scroll-cue.html %}
    </div>
</div>

&nbsp;

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

<div id="instagram" class="main">
  <div class="wrap">
    <h1 id="posts">Latest Pictures from <a target="_blank" href="https://www.instagram.com/jasonswingen/">JS-Outdoors on Instagram</a></h1>
  </div>
    {% include snapwidget.html %}
</div>
