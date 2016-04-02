---
layout: default
permalink: /
title: "Latest Posts"
image:
---

<div class="page-lead" style="background-image:url(/images/2015_MT_Hunt_11.jpg)">
    <div class="wrap page-lead-content">
        <h1>JS-Outdoors</h1>
        <h2>My name is Jason Swingen and I am a Multi-species angler, big-game hunter, and avid outdoorsman living in Minnesota. Check out my recent fishing and hunting adventures below!</h2>
        <a href="#posts" class="btn-inverse">Latest Posts</a>
        &nbsp;
        <span> or </span>
        &nbsp;
        <a href="/fishing/fishing-report" class="btn-inverse">Fishing Reports</a>
    </div>
</div>
&nbsp;

<div class="main">
  <div class="wrap">
    <h1 id="posts">Latest Posts</h1>
    <div class="tiles">
    {% for post in site.posts %}
        {% include post-grid.html %}
    {% endfor %}
    </div><!-- /.tiles -->
  </div>
</div>
