---
layout: archive
permalink: /
title: "Latest Posts"
---

<div class="tiles">
  text
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
