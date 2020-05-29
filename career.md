---
title: Career
layout: page
---

<p class="right animated">To be continued, つづく </p>

<table class="table-career animated">
{% for career in site.data.career %}
{% assign loopindex = forloop.index %}
{% include career-item.html %}
{% endfor %}
</table>

<br>
<br>
<br>


<div>
{% for career in site.data.career %}
{% assign loopindex = forloop.index %}
{% include career-resource.html %}
{% endfor %}
</div>
<iframe src="https://player.vimeo.com/video/423963855" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
<br>


{% include social-links.html %}






