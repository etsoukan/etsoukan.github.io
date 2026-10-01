---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% if site.author.googlescholar %}
<p class="publication__intro">Also on <a href="{{ site.author.googlescholar }}">Google Scholar</a>.</p>
{% endif %}

{% for post in site.publications reversed %}
  {% include publication-entry.html %}
{% endfor %}
