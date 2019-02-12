---
layout: default
permalink: /
image:
title: JS-Outdoors | Fishing & Hunting Tips for the Midwestern Outdoorsman
excerpt: Hunting and Fishing stories, tips, and techniques. Written for and by a Midwestern Outdoorsman. From hunting mule deer in MT to fly fishing for steelhead in MN and everything in between.
---

<div id="content" class="main">

<!-- <div class="page-lead" style="background-image:url(/images/2017-king-salmon.jpg)">
    <div class="page-lead-content">
      <div class="page-lead-title">
        <p>Welcome to JS-Outdoors. Hunting and Fishing stories written for and by the Midwestern Outdoorsman. If you have a passion for the outdoors too, then check out some of my most recent adventures below!</p>
        <a class="btn" target="_blank" href="#instagram">Follow Along</a>
        <a class="btn btn-accent" href="#posts">View Posts</a>
      </div>
    </div>
</div> -->

{% include jumbotron.html %}


<!-- <div class="banner">
  <div class="center">
    <p>
      <span>Get notified when I add new articles </span>
      <span class="buttons">
        <a class="btn-social instagram" target="_blank" href="https://www.instagram.com/jasonswingen/">Instagram</a>
        <a class="btn-social twitter" target="_blank" href="https://twitter.com/jasonswingen">Twitter</a>
      </span>
    </p>
  </div>
</div> -->




<div class="section">
  <div id="main" role="main" id="posts">
  <div class="wrap centerpage animate fadeInUp">
  <!--   <h1><a href="{{ domain }}/blog.html">Recent Posts</a></h1> -->
      <div class="tiles">
        {% for post in site.posts limit:16 %}
            {% include post-grid.html %}
        {% endfor %}
      </div>
  </div>
  </div>
</div>
<div class="center">
  <p>
    <span class="">
      <a class="btn btn-accent" href="/blog.html">View More Posts</a>
    </span>
  </p>
</div>



<div class="section">
  <div class="wide">
      {% include youtube-grid.html %}
  </div>
</div>

<div class="banner">
  <div class="center">
    <p>
      <span>Subscribe on </span>
      <span class="buttons">
        <a class="btn-social youtube" target="_blank" href="https://www.youtube.com/channel/UCJuAVRLRC6AFV-YqN1a_6EQ">YouTube</a>
      </span>
    </p>
  </div>
</div>

<div class="section">
   {% include snapwidget.html %}
</div>

<div class="banner">
  <div class="center">
    <p>
      <span>Follow on </span>
      <span class="">
        <a class="btn-social instagram" target="_blank" href="https://www.instagram.com/jasonswingen/">Instagram</a>
      </span>
    </p>
  </div>
</div>

</div>
