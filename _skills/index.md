---
title: Skills
layout: default
overview: true
---
# Skills
Gearshift Workshop is a relatively low-magic setting. The magic which does exist is usually used to create technology to improve the world. The skills in this setting are chosen to reflect this low-magic, developing-technology, forward-looking world.

The ability to use magic is innate For a character to use magic, they must have at least one rank in that magic skill at character creation or their class skills must include that magic skill. After character creation, any magic skills with zero ranks are permanently unavailable for that character.

{% for skill in site.skills %}
	{%- if skill.overview != true and skill.new -%}
		{{ skill.content }}
	{%- endif -%}
{% endfor %}

{% for skill in site.skills %}
	{%- if skill.overview != true and skill.new != true -%}
		{{ skill.content }}
	{%- endif -%}
{% endfor %}