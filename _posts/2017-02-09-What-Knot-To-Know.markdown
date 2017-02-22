---
layout: post
title: "What Knot To Know: The Fishing Knot Guide"
modified:
categories: [fishing]
tags: [tips, fishing, ice-fishing, fly-fishing, tips]
published: True
comments: True
excerpt: The knots that you need to know, when you should use them, and why they are used over other knots.
image:
  feature: Fishing_Knot.jpg
  teaser: Fishing_Knot.jpg
  thumb: Fishing_Knot.jpg
date: 2017-02-09T07:21:38-06:00
---

Just like learning how to tie your shoes when you were a kid, learning how to tie the essential knots of fisherman will keep you from tripping up. Now However, the steaks are much higher. If you take the time to research the best rods, reels, lines, and lures, as well as spend the time figuring where to find fish and how to catch them, don't you want the reassurance that your knots are going to hold up when you have a new personal best fish at the end of your line.

If you ever over worry about what pound test you should use, then you should be equally worried about tying a knot that will hold up to that same strength.

> "Your fishing line is only as strong as its weakest link"

Here is a list of the knots that I use on a regular basis. Most of them have a specific time and place where they should be used, while others can be used for many different applications.

## The Knots We Will Cover

{% for link in site.data.knots %}
The <strong><a href="#{{ link.Name }}">{{ link.Name }} knot</a></strong> is used for tying <i>{{ link.Application }}</i> and is <i>{{ link.Ease }}</i> to tie. This knot is <i>{{link.Importance }}</i> important to know.
{% endfor %}

## New Fisherman - The Knots You Need To Learn First
If you are brand new to fishing and are learning to tie fishing knot for the first time the most important knots that will let you tie your main line from your spool to your leader and your leader to your lure. Those knots are the <a href="#Arbor">Arbor</a>, the <a href="#Double Uni">Double Uni</a>, the <a href="#Improved Clinch">Improved Clinch</a>, and the <a href="#Palomar">Palomar Knot</a>.

## Stubborn Fisherman
If you are stubborn and only want to learn one knot and use if for every application you should learn how to tie the <a href="#Uni">Uni</a> knot. This knot is made to tie your line to a hook, but in a pinch can be used to tie your line onto your spool, or even tie two lines together through the use of a <a href="#Double Uni">Double Uni</a>

<hr>

## Instructions

{% for link in site.data.knots %}

<h3 id="{{ link.Name }}"> {{ link.Name }} Knot </h3>

{% if link.Application %}
<h5>Applictions</h5>
<p>This knot if used to connect your <strong>{{ link.Application }}</strong>.</p>
{% endif %}

{% if link.Importance %}
<h5>Importance</h5>
<p>{{ link.Importance }}.</p>
{% endif %}

{% if link.Ease %}
<h5>Ease</h5>
<p>This knot is <strong>{{ link.Ease }}</strong> to tie.</p>
{% endif %}

{% if link.Description %}
<h5>Description</h5>
<p>{{ link.Description }}</p>
{% endif %}

{% if link.Media %}
<h5>Instructions</h5>
<img src="{{ link.Media }}" alt="{{ link.Name }} Knot" title="{{ link.Name }} Knot" />
{% endif %}

{% endfor %}