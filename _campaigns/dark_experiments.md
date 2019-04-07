---
title: Dark Experiments
layout: default
overview: true
---
# Dark Experiments
_Pulling back the veil on the dark side of Gearshift._

<gm-note>
<i class="fa fa-info-circle fa-2x fa-fw"></i>

For this campaign, its recommended the player characters all know each other and are familiar with the general layout of the city of Gearshift. For the opening scene, establish why the PCs have gathered in this park about midday. It could be as simple of a reason as "getting lunch at a popular food stand".
</gm-note>

### Chapters
{% for chapter in site.campaigns %}
	{%- if chapter.dark_experiments -%}
		[**{{ chapter.dark_experiments}} {{ chapter.title }}**]({{ chapter.url }}) — {{ chapter.description}}
	{%- endif -%}
{% endfor %}