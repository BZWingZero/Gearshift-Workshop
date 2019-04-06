---
title: Talents
layout: default
overview: true
---
# Talents
Talents are a representation of specialized techniques a character has mastered either through natural aptitude or intense practice and study.

{% for talent in site.talents %}
	{%- if talent.overview != true and talent.new -%}
		{{ talent.content }}
	{%- endif -%}
{% endfor %}

{% for talent in site.talents %}
	{%- if talent.overview != true and talent.new != true -%}
		{{ talent.content }}
	{%- endif -%}
{% endfor %}