---
layout: post
title: "How To Catch Bass On The Fly"
modified:
categories: [fishing]
tags: [fishing, gear, fly-fishing, bass, shop]
published: False
comments: True
ads: False
excerpt: Want to catch bass on a fly rod? All the fly fishing equipment and techniques you need to catch bass on a fly rod.
image:
  feature: bass-on-the-fly.jpg
  teaser: bass-on-the-fly.jpg
  thumb: bass-on-the-fly.jpg
date: 2019-08-08T05:24:24-05:00
---

They may be no better species to learn how to fly fish for than a bass. With that being said, bass fishing isn't just a beginner's fish. They fight extremely hard, fly out of the water, and will crush a large variety of flies.

If you want to learn the equipment, techniques, and places to catch big bass on a fly rod, then you've come to the right place.



## Where to Fish

### Lakes, Rivers, and Streams

## How to Fish

### Retrieves

## Equipment

### Rod

### Reel

### Line

### Leader

### Flies


## My Current Selection of Bass Fishing Fly Gear

{% for item in site.data.bassgear %}

{% if item.Name %}
##### {{item.Name}}
{% endif %}

{% if item.Description %}
{{item.Description}}
{% endif %}

{% if item.Link %}
<span title="Buy {{item.Name}} on Amazon">{{item.Link}}</span>
{% endif %}

{% endfor%}

<!-- {% for item in site.data.gear %}
{% if item.Link %}
<span style="float:left;width:33%;height:300px;">{{item.Link}}</span>
{% endif %}
{% endfor%} -->

{% include disclosure.html %}
