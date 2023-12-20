---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Below is a selected list of my project:

{% include base_path %}

{% for post in site.projects %}
    {% include archive-single.html %}
{% endfor %}