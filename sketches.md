---
layout: boxleft
title: sketches
box-color: "#f3f3f3"
permalink: /sketches/
images: "/assets/images/illustrations/sketches.jpg"
text: "Here are some sketches from little notebooks I always carry around.<br> I've made them over the years and they are the result of my experiences with new techniques and materials." 
---

<div class="row">
	{% for i in (1..39) %}
		<div class="col-md-6">
			<a class="post-images" href="/assets/images/illustrations/sketches/{{ i }}.jpg" data-lightbox="sketches-illustrations"><img src="/assets/images/illustrations/sketches/{{ i }}.jpg" class="post-images"></a>
		</div>
	{% endfor %}
</div>