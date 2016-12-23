---
title: Blog
layout: page
description: What I've been doing
image: assets/images/pillars-of-creation.jpg
nav-menu: true
comments: false
---
<div id="main" class="alt">
{% for post in site.posts %}
	<div >
		<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
	</div>
{% endfor %}
</div>