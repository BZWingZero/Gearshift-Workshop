---
title: Dark Experiments
layout: 2_col
overview: true
hidden: true
---
# Dark Experiments
_Pulling back the veil on the darker side of Gearshift._

<gm-note>
<i class="fa fa-info-circle fa-2x fa-fw"></i>

For this campaign, its recommended the player characters all know each other and are familiar with the general layout of the city of Gearshift. For the opening scene, establish why the PCs have gathered in a small park about midday. It could be as simple of a reason as "getting lunch at a popular food stand".
</gm-note>

<skillblock markdown="block">
A few symbols are used throughout this campaign:

<i class="fa fa-map-marker fa-2x fa-fw"></i>  
:  The pin symbol indicates an important location or a location where a setpiece event occurrs.

<i class="fa dice fa-2x fa-fw">s</i>  
: The explosion symbol is used for a combat encounter.

<i class="fa symbols fa-2x fa-fw">t</i>
: The triumph symbol shows where the narrative portion continues after the completion of an encounter.

</skillblock>

### Chapters
{% for chapter in site.campaigns %}
	{%- if chapter.dark_experiments -%}
		[**{{ chapter.dark_experiments}} {{ chapter.title }}**]({{ chapter.url | relative_url }}) — {{ chapter.description}}
	{%- endif -%}
{% endfor %}