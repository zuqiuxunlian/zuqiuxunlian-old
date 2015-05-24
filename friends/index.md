---
layout: archive
title: "训友介绍"
date: 2014-05-30T11:39:03-04:00
modified:
excerpt: "关于训练营的朋友组织的球队."
tags: []
image:
  feature:
  teaser:
  
---

<div class="tiles">
{% for post in site.categories.friends %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->