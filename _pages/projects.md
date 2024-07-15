---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---
**You can find more details about each project on its website by clicking the title of the corresponding project.**

[Logic Learning from Demonstrations for Multi-step Manipulation Tasks in Dynamic Environments](https://sites.google.com/view/logic-lfd/)

<div style="text-align:justify;">
This project aims to design a reactive task and motion planning algorithm with one single demonstration for long-horizon manipulation tasks in dynamics tasks. It also results in an LfD that can imitate, generalize, and reactive to disturbances for multi-step tasks in real world. We tested the method in several tasks and are targeting on to extent it for building intelligent robot assistants at home.
</div>
<br/>

[Representing Robot Geometry as Distance Fields: Applications to Whole-body Manipulation](https://sites.google.com/view/lrdf)

<div style="text-align:justify;">
This project represents a serial robot arms with Signed Distance Functions (SDF) with kinematic chain awareness. This differentiaable implicit representation enables efficient minimal distance and gradient query, which thus facilitates the design of dual-arm self-collision avoidance and whole-arm lifting big and bulky objects. I am mainly invovled in the dual-arm self-collision section.
</div>
<br/>

[Learning and Generalizing Variable Impedance Manipulation Skills from Human Demonstrations](../_projects/projects-3.md)
<div style="text-align:justify;">
This project aims to enable robot arms learn variable impedance manipulation skills from multiple demonstrations for pouring tasks in human-centric environments.
</div>
<br/>

[Robot Learning to Move Like Animals: Sim2Real Transfer of DRL for Quadrupled Robots Learning Locomotion Gaits](../_projects/projects-2.md)
<div style="text-align:justify;">
This project aims to reproduce the results presented in the paper titled <a href="https://arxiv.org/abs/2004.00784">Learning Agile Robotic Locomotion Skills by Imitating Animals</a> on our self-designed multi-modal quadruped robot. I was involved in this project when I was doing my research internship at Tencent Robotics X Lab and my work mainly focus on the Sim2Real part. During my internship, I managed to transfer gaits learned in simulation to the real quadruped robot with a 100% success rate.
</div>
<br/>

[Learning Optimal Manipulation Skills in a Human-like Way for Contact-rich Tasks](../_projects/projects-1.md)
<div style="text-align:justify;">
This project targets on learning optimal variable impedance manipulation skills with human demonstrations in a residual reinforcement learning manner for contact-rich tasks, e.g. peg insertion. I managed to deploy it on a 7-axis Franka Emika robot arm by integrating deep reinforcement learning and imitation learning with Python, C++, and ROS.
</div>
<br/>

<!-- load other projects in _projects at the end
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %} -->