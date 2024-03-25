---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
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

# Publications
#### &nbsp; ####

<div class="jumbotron">
### Journal articles
{% bibliography --query @article %}
</div>

<div class="jumbotron">
### Invited talks
{% bibliography --query @incollection[keywords ^= invited] %}
</div>

<div class="jumbotron">
### Conference presentations (First author)
{% bibliography --query @incollection[keywords ^= conference] %}
</div>
