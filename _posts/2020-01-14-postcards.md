---
layout: boxleft
title: postcards
box-color: "#f3f3f3"
permalink: /illustration/postcards/
images: /assets/images/homepage/4.jpg
text: "These are some postcards I made for a friend by recycling old milk boxes and covering them with magazines, newspapers and my drawings."
---

<div class="row">
	{% for i in (1..14) %}
		<div class="col-md-6">
			<a class="post-images" href="/assets/images/illustrations/postcards/{{ i }}.jpg" data-lightbox="postcards-illustrations"><img src="/assets/images/illustrations/postcards/{{ i }}.jpg" class="post-images"></a>
		</div>
	{% endfor %}
</div>