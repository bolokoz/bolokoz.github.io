---
title: Projects
layout: page
description: Ongoing and finished projects
image: /assets/images/voyager.jpg
nav-menu: true
comments: false
---

{% for project in site.projects %}
	<div >
		<h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
	</div>
{% endfor %}