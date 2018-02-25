---
layout: projects
permalink: /projects/
---

<div id="wrapper">
	<!-- Main -->
	<div id="main">
		{% for project in site.data.projects %}
		<article class="thumb">
			<a href="{{ project.url }}" target="_blank"><img src="{{ site.url }}{{ site.baseurl }}/assets/projects/images/{{ project.image }}" alt=""/></a>
			<h2 style="font-weight: bold">{{ project.title }}</h2>
		</article>
		{% endfor %}
	</div>
</div>

