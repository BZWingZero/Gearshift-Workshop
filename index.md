---

layout: default
---
{% for location in site.world %}
{%- if location.title == 'Ventia' -%}
{{ location.content | markdownify }}
{%- endif -%}
{% endfor %}

{% for collection in site.collections %}
{% assign collection_name = collection.label %}
{% for page in collection.docs %}
	{%- if page.overview == true and page.hidden != true -%}
		## [{{ page.title }}]({{ page.url | relative_url }})
	{%- endif -%}
{% endfor %}
{% endfor %}