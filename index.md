---

layout: default
---
{% for location in site.world %}
{%- if location.title == 'Ventia' -%}
{{ location.content | markdownify }}
{%- endif -%}
{% endfor %}