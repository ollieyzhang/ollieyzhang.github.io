---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
**You can find more details about each project on the its website by clicking the title of the corresponding project**

[Representing Robot Geometry as Distance Fields: Applications to Whole-body Manipulation](https://sites.google.com/view/lrdf)

<div style="text-align:justify;">
This project represents a serial robot arms with Signed Distance Functions (SDF) with kinematic chain awareness. This differentiaable implicit representation enables efficient minimal distance and gradient query, which thus facilitates the design of dual-arm self-collision avoidance and whole-arm lifting big and bulky objects. I am mainly invovled in the dual-arm self-collision section.
</div>

<!-- load other projects in _projects at the end -->
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}