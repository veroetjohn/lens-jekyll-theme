---
layout: home
title: Lens by HTML5 UP
---

<!-- Thumbnail -->
<section id="thumbnails">{% for photo in site.data.photos_listing %}
	<article>
		<a class="thumbnail" href="{{ site.image_dir }}{{ photo.image }}" data-position="left center"><img src="{{site.image_tn_dir }}{{ photo.thumbnail }}" alt="" /></a>
		<h2>{{ photo.title }}</h2>
		<p>{{ photo.caption }}</p>
	</article>
{% endfor %}</section>
