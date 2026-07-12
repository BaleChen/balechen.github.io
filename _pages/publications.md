---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<p class="publication-scholar-note">You can also find my papers on my <a href="{{ site.author.googlescholar }}">Google Scholar profile</a>.</p>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include publication-entry.html %}
{% endfor %}
