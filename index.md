---
layout: archive
permalink: /
title: ""
---

<div class="tiles">
{% for snippet in site.pages %}
    {% if snippet.layout == 'snippet' %}
    	{% include snippet-grid.html %}
    {% endif %}
{% endfor %}
</div><!-- /.tiles -->
