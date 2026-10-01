---
layout:     page
title:      Papers
permalink:  /papers/
---

<ul>
{%- for file in site.static_files -%}
  {%- if file.path contains '/papers/' and file.extname == '.pdf' %}
  <li><a href="{{ file.path | relative_url }}" target="_blank">{{ file.basename }}</a></li>
  {%- endif -%}
{%- endfor %}
</ul>
