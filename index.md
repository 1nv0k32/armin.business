---
layout: default
---

<h1>{{ site.author.name }}</h1>
<p class="tagline">{{ site.tagline }}</p>

<p class="bio">
  A short paragraph about who you are and what you do. Replace this text in
  <code>index.md</code>.
</p>

<ul class="links">
{% for link in site.links %}
  <li><a href="{{ link.url }}"{% unless link.url contains 'mailto:' %} rel="me noopener" target="_blank"{% endunless %}>{{ link.name }}</a></li>
{% endfor %}
</ul>
