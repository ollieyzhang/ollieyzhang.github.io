---
title: "Robot Learning to Move Like Animals: Sim2Real part"
excerpt: "**Project Description**: This project aims to reproduce the results presented in the paper titled **[Learning Agile Robotic Locomotion Skills by Imitating Animals](https://xbpeng.github.io/projects/Robotic_Imitation/2020_Robotic_Imitation.pdf)** on our self-designed multi-modal quadruped robot. I was involved in this project when I was doing my research internship at Tencent Robotics X Lab and my work mainly focus on the Sim2Real part. During my internship, I managed to transfer gaits learned in simulation to the real quadruped robot with a 100% success rate.
<br />
<br />
**Overview**:
<br/>
<br/>
<img src='/images/deep_mimic/deep_mimic_framework.svg'>"
collection: projects
---

<div align='center'>
    <font size='28'> Robot Learning to Move Like Animals: Sim2Real part </font> 
</div>

More details about how I manage to control the success of Sim2Real will be presented with a PPT later.

[comment]: <> (## Introduction)

[comment]: <> (Robots can learn agile gaits by imitating animals. For example, Peng at al. presented an interesting deep mimic framework in **[Learning Agile Robotic Locomotion Skills by Imitating Animals]&#40;https://xbpeng.github.io/projects/Robotic_Imitation/2020_Robotic_Imitation.pdf&#41;** where a quadruped robot learns to walk and turn like animals. In their work, they developed a Reinforcement Learning&#40;RL&#41; based skill learning framework to imitate animal's motions in simulation and transferred the learned gaits from simulation to reality &#40;Sim2Real&#41; with domain randomization and domain adaptation modules. In this page, I will present the research work &#40;with a focus on the Sim2Real part&#41; that aims to reproduce the results in Peng's paper on our self-designed dog &#40;max1&#41; with our collected MoCap motions. This work was done when I was doing a research internship at Tencent Robotics X Lab.)