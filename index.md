---
layout: default
permalink: /
image:
---

<div id="content" class="main">

  <div class="page-lead" style="background-image:url(/images/Smallie_Fly.jpg)">
      <div class="page-lead-content">
        <div class="page-lead-title slideleft">
          <!-- <h1>Welcome to</h1> -->
          <img src="images/JS_OUTDOORS_long_logo.jpg" alt="">
          <p>Brought to you by Jason Swingen. A Minnesotan that loves to hunt and fish. If you have a passion for the outdoors too please check out some of my most recent adventures below!</p>
        </div>
      </div>
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
        {% include youtube-grid.html %}
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

  <div id="instagram" class="">
    {% include device.html %}
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
    {% include subscribe.html %}
  </div>

</div>
