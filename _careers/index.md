---
title: Careers
layout: default
overview: true
---
# Careers

The world of Gearshift is generally peaceful and the vocations within it are as varied as its inhabitants. From technical to the arcane, pensive or daredevil, there are roles for everyone

<cardwrap>
{% for career in site.careers %}
	{%- if career.overview != true -%}
	<card>
		{{ career.content | markdownify}}
	</card>
	{%- endif -%}
{% endfor %}
</cardwrap>