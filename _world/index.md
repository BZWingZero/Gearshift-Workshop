---
title: Ventia
layout: 2_col
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
## [{{ location.title }}]({{ location.url }})
{{ location.description }}
{%- endif -%}
{% endfor %}
</skillblock>

<!-- ## [Gearshift]()
A City-State more powerful than any other nation in Ventia. -->