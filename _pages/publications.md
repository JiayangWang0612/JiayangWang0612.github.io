---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Preprints

{% assign preprints = site.publications | where: "category", "preprints" | sort: "date" | reverse %}
{% for post in preprints %}
  {% include publication-entry.html %}
{% endfor %}

{% assign articles = site.publications | where_exp: "item", "item.category != 'preprints'" | sort: "date" | reverse %}
{% if articles.size > 0 %}
<h2>Journal articles and other publications</h2>
{% for post in articles %}
  {% include publication-entry.html %}
{% endfor %}
{% endif %}
