---
title: "**STANCE**: Locomotion Adaptation over Soft Terrain"
collection: research
---

<img src="/assets/images/stance.png"
     alt="Markdown Monster icon"
     />

## Overview
Whole-body Control (**WBC**) has demonstrated remarkable result in dealing with multiple tasks while reasoning about the  the robot’s dynamics, actuation limits and interaction with the environment. It emerged as an important framework in locomotion control for legged robots. 

However, most of **WBC** frameworks fail to generalize beyond rigid terrains. Legged locomotion over soft terrain is difficult due to the presence of unmodeled contact dynamics that **WBC**s do not account for. This introduces uncertainty in locomotion and affects the stability and performance of the system.

To this end, we propose a novel soft terrain adaptation algorithm called **STANCE**: **S**oft **T**errain **A**daptation a**n**d **C**ompliance **E**stimation. **STANCE** consists of a **WBC** that exploits the knowledge of the terrain to generate an optimal solution that is contact consistent and an online terrain compliance estimator that provides the **WBC** with terrain knowledge. 

**STANCE** can adapt online to any type of terrain (stiff or soft) without pre-tuning. As a result, HyQ was capable of adapting its locomotion strategy and remain contact consistent. **STANCE** allows HyQ to traverse multiple terrains with different compliances and to transition between them. 

## Selected publication(s): 
> [__STANCE: Locomotion Adaptation over Soft Terrain.__](https://arxiv.org/pdf/1904.12306.pdf) <br>
S. Fahmi, M. Focchi, A. Radulescu, G. Fink, V. Barasuol and C. Semini <br>
preprint, Arxiv, 2019

## Contact: 
Contact: Shamel Fahmi and Michele Focchi

## Media:

<iframe width="560" height="315" src="https://www.youtube.com/embed/rINRnicv7_I?autoplay=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
