---
layout: default
---

<h1>{{ site.title }}</h1>
<p class="tagline">{{ site.tagline }}</p>

<ul class="links">
{% for link in site.links %}
  <li><a href="{{ link.url }}"{% unless link.url contains 'mailto:' %} rel="me noopener" target="_blank"{% endunless %}>{{ link.name }}</a></li>
{% endfor %}
</ul>
