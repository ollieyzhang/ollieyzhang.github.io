---
title: "Learning Optimal Manipulation Skills in a Human-like Way for Contact-rich Tasks"
excerpt: "This project targets on learning optimal variable impedance manipulation skills with human demonstrations in a residual reinforcement learning manner for contact-rich tasks, e.g. peg insertion. I managed to deploy it on a 7-axis Franka Emika robot arm by integrating deep reinforcement learning and imitation learning with Python, C++, and ROS."
collection: projects
---
<style>
body {
    background-color: #f0f0f0; /* Light grey background */
}
</style>

<div align='center'>
    <font size='20'> Learning Optimal Manipulation Skills in a Human-like Way for Contact-rich Tasks</font> 
</div>

# Abstract
---
<div style="text-align:justify;">
Imitation Learning(IL) algorithms have shown great success in human-robot manipulation skills transferring. However, they assume access to optimal human demonstrations and don't explicitly model the environment dynamics, which limits the optimality of learned manipulation skills and their performance in solving contact-rich tasks. Humans learn professional manipulation skills through imitating experts and improving the learned skills from trials and errors. In this letter, we develop a human-like safe optimal manipulation skills learning framework for solving contact-rich tasks. This framework combines IL methods with Reinforcement Learning (RL) algorithms for learning initial manipulation skills by imitating human demonstrations and further optimizing the initial skills with trials and errors. Furthermore, we propose using demonstration space to constrain the learned optimal actions in continuous action space for the safe exploration of RL agents. We also further develop our learning framework to learn optimal variable impedance manipulation skills for avoiding large contact forces and ensuring interaction safety. Simulation and real-world experiments on a 7 DoF redundant robot manipulator for peg insertion tasks validate the effectiveness of our proposed method.
</div>


# Overview:
---
<img src='/images/optimal_vic.svg' alt="Overview of the proposed method." height="300" style="display: block; margin-left: auto; margin-right: auto;"/>