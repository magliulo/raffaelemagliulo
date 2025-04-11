---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">
  <i class="ai ai-google-scholar"></i>
  <a href="{{ site.author.googlescholar }}" target="_blank" rel="noopener">Google Scholar</a>
</div>
{% endif %}

{% if site.author.orcid %}
<div class="wordwrap">
  <i class="ai ai-orcid"></i>
  <a href="{{ site.author.orcid }}" target="_blank" rel="noopener">ORCID</a>
</div>
{% endif %}

{% if site.author.pubmed %}
<div class="wordwrap">
  <i class="ai ai-pubmed"></i>
  <a href="{{ site.author.pubmed }}" target="_blank" rel="noopener">PubMed</a>
</div>
{% endif %}

{% if site.author.researchgate %}
<div class="wordwrap">
  <i class="ai ai-researchgate"></i>
  <a href="{{ site.author.researchgate }}" target="_blank" rel="noopener">ResearchGate</a>
</div>
{% endif %}

<br>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
