---
title: Ventia
layout: 2_col
parent: world
---
# The World of Ventia

Airships roam the skies, and fantastic creations abound powered by crystallized &aelig;ther distilled by &AElig;thertechs the world over. This &aelig;therite is used throughout society for supercharging weapons to powering mechanized golems and even clockwork dragonflys flitting from place to place.

Welcome to the Ventia! It is a world of adventure and invention. A place where creation and ideas are celebrated. It is a time of discovery with new devices being created and places being discovered beyond the mapped world. Yet, not everyone is benefiting from these discoveries.

Those who control the production and distribution of the new inventions wield enormous power leaving those without access to scrounge for the leftover scraps. Society in Ventia separated into classes and only the occasional generosity of the wealthy allow someone to climb out of poverty.

The barons and merchants have access the capital and &aelig;therite they need to maintain their position; in recent decades their companies grow unchecked. The waning influence of the traditional rulers has been maintained only while benefiting the merchants.

<div class="fullwidth"></div>

<skillblock markdown="block">
{% for location in site.world %}
{%- if location.parent == 'ventia' -%}
## [{{ location.title }}]({{ location.url | relative_url }})
{{ location.description }}
{%- endif -%}
{% endfor %}
</skillblock>

## Some unsorted info: 
* For centuries mages seculded themselves and only the wealthiest (kings, lords etc) could afford their services; which they used to secure their dynasties. Magic wasn't a part of daily life for most.
* A tense truce had been formed between the kingdoms and aside from minor flareups along borders, mostly stable.
* About 78 years ago, a master aethertech at the Institute of Arcane Research figured out how to condense raw aether as a fine powder (aether powder). This powder could then be compressed and heated forming heptagonal prisms of pure aetherite. The magic contained in the crystals was miniscule compared to the skill of trained mages. However, these aetherite crystals could be used by anyone.
* As the process for condensing the aetherpowder and making aetherite spread and the general public could get their hands on it, they began experimenting with it. This created a technological and industrial revolution with brilliant new minds using magic in ways the Mage orders never dreamed.
* The leaders of the nations became nervous as many had maintained their grip of power through Mages, and with the populace now gaining access to the once-restricted power their control was threatened.

**Themes**: invention, discovery, potential political upheaval 