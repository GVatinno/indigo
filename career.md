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

{% include social-links.html %}






