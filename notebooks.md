---
layout: page
title: Notebooks
description: Documentation mostly from my university course
image: /assets/images/pale-blue-dot.jpg
nav-menu: true
comments: false
---

{% for notebook in site.notebooks %}
	<div >
		<h2><a href="{{ notebook.url }}">{{ notebook.title }}</a></h2>
	</div>
{% endfor %}
