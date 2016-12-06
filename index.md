---
layout: default
permalink: /
image:
---

<div class="page-lead" style="background-image:url(/images/2015_MT_Hunt_18.jpg)">
    <div class="wrap page-lead-content">
        <!-- <h1>JS-OUTDOORS</h1> -->
        <h1>Fish - Hunt - Learn</h1>
        <p>Sign up or follow me on instagram to stay informed about new fishing and hunting information, as well as stories, reports, and reviews!</p>
        <a href="https://www.instagram.com/jasonswingen/" target="_blank" class="btn-accent">Follow on Instagram</a>
        <span><b>- or - </b></span>
        <a href="#subscribe" class="btn">Subscribe</a>
    </div>
</div>

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

<div id="subscribe" class="wrap">
{% include subscribe.html %}
<div>
