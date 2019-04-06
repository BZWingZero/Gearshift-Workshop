---
title: The Five Races
layout: default
overview: true
---
# Races

Many races inhabit the Ventia, most are isolated to small tribes. Five primary races are common: The technical specialist Dwarves; the studious yet reclusive Elves, the inquisitive Halflings; the varied tribes of Humans, and the proud warrior Orcs.

<cardwrap>
{% for race in site.races %}
	{%- if race.overview != true -%}
	<card>
		{{ race.content }}
	</card>
	{%- endif -%}
{% endfor %}
</cardwrap>