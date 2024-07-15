---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="wordwrap">You can find more details about on the project website by clicking the title of the corresponding project.</a>.</div>

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
