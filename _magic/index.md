---
title: Magic
layout: 2_col
overview: true
---
# Magic
Mages practiced the discipline through the generations across Ventia. Over time it became well documented and its study formalized. Only in recent times with the process of condensing &aelig;ther have the masses been able to access this once limited technique. This has led to the development of a new career, the **&AElig;thertech**.

## Recent Innovations:<br/><small>&AElig;ther Powder and &AElig;therite</small>

When &aelig;ther is crystallized, it becomes attuned to one of these domains. Skill and ingenuity can allow a master to explore its versatility. The unexpected uses cause the most innovation, leading to new areas of study.

## The Five Domains
Centuries passed during which time Mages cultivated schools of knowledge to research Magic and its rules. Their research determined magic could be divided into five broad domains within Ventia.

### Magic Skills and Actions
<skillblock markdown="block">

|  | Flow | Force | Growth | Moderate | Shock |
|:--|:-:|:-:|:-:|:-:|:-:|
| Attack |<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|
| Augment ||<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|||
| Barrier ||<i class="accent fa fa-cog"></i>|||<i class="accent fa fa-cog"></i>|
| Curse ||||<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|
| Dispel |<i class="accent fa fa-cog"></i>|||<i class="accent fa fa-cog"></i>||
| Heal |<i class="accent fa fa-cog"></i>||<i class="accent fa fa-cog"></i>|||
| Utility |<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|<i class="accent fa fa-cog"></i>|

</skillblock>

{% for magic in site.magic %}
	{%- if magic.overview != true -%}
		<skillblock>
		{{ magic.content | markdownify}}
		</skillblock>
	{%- endif -%}
{% endfor %}