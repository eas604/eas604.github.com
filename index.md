---
layout: page
title: Objects in Heap Space
tagline: "\"Well, here I am.\""
---

## Posts
<div class="jumbotron">
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date: "%Y-%b-%-d" }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>

## About

<div class="col-md-6">
<h3>This Blog</h3>

<p>This is just a place for me to muse about topics that interest me. These things may include (but are not limited to):
programming, IT, running, Spanish, transportation infrastructure, craft beer, <i>Firefly</i>, and reasons why
<a href="http://blog.patrickrothfuss.com/">Patrick Rothfuss</a> is the most underrated author of our generation.</p>

</div>

<div class="col-md-6">
<h3>The Author</h3>

<p>My name is Edwin Sheldon. I'm a software engineer who has worked in the GIS and HIT industries. I code mainly in Python,
C#, and JavaScript. I'm a bit of a Linux/Unix enthusiast. Es mi dios la libertad.</p>
</div>
