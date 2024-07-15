---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---
**You can find more details about each project on its website by clicking the title of the corresponding project**

[Logic Learning from Demonstrations for Multi-step Manipulation Tasks in Dynamic Environments](https://sites.google.com/view/logic-lfd/)

<div style="text-align:justify;">
This project aims to design a reactive task and motion planning algorithm with one single demonstration for long-horizon manipulation tasks in dynamics tasks. It also results in an LfD that can imitate, generalize, and reactive to disturbances for multi-step tasks in real world. We tested the method in several tasks and are targeting on to extent it for building intelligent robot assistants at home.
</div>

[Representing Robot Geometry as Distance Fields: Applications to Whole-body Manipulation](https://sites.google.com/view/lrdf)

<div style="text-align:justify;">
This project represents a serial robot arms with Signed Distance Functions (SDF) with kinematic chain awareness. This differentiaable implicit representation enables efficient minimal distance and gradient query, which thus facilitates the design of dual-arm self-collision avoidance and whole-arm lifting big and bulky objects. I am mainly invovled in the dual-arm self-collision section.
</div>

[Learning and Generalizing Variable Impedance Manipulation Skills from Human Demonstrations](../_projects/projects-3.md)
<div style="text-align:justify;">
This project aims to enable robot arms learn variable impedance manipulation skills from multiple demonstrations for pouring tasks in human-centric environments.
</div>

<!-- load other projects in _projects at the end -->
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}