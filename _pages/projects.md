---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="wordwrap">You can find more details about each project on the its website by clicking the title of the corresponding project**.</div>

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
