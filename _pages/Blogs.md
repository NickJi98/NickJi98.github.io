---
title: "Blogs"
layout: gridlay
sitemap: false
permalink: /Blogs/
---

<style>
.jumbotron{
    padding:3%;
    padding-top:10px;
    padding-bottom:5px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

# My Blogs
#### &nbsp; ####

{% assign sorted = site.posts | sort: "order" %}
{% for post in sorted %}
<div class="jumbotron">
<div class="col-xs-12 col-sm-12 col-lg-12 clearfix">
  <div class="well">
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {{ post.excerpt | strip_html }}
  </div>
</div>
</div>
{% endfor %}
