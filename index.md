---
layout: default
title: Home
---
<ul class="catalogue">
{% for page in site.pages %}
{% if page.blog == true %}
{% include post-list.html %}
{% endif %}
{% endfor %}
</ul>
