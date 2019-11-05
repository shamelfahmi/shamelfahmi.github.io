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
S. Fahmi, M. Focchi, A. Radulescu, G. Fink, V. Barasuol, and C. Semini, "[__STANCE: Locomotion Adaptation over Soft Terrain__](https://iit-dlslab.github.io/papers/fahmi19tro.pdf)," IEEE Transactions on Robotics (T-RO), Oct. 2019.

## Cite as:
```
{% raw %}
@Article{Fahmi2019TRO,
  Title                    = {{STANCE}: Locomotion Adaptation over Soft Terrain},
  Author                   = {S. {Fahmi} and M. {Focchi} and A. {Radulescu} 
                           and G. {Fink} and V. {Barasuol} and C. {Semini}},
  Journal                  = {{IEEE} Trans. Robot. ({T-RO})},
  Year                     = {2019},
  Month                    = {Oct.},
  Pages                    = {1--15},
}
{% endraw %}
```
## Media:
<iframe width="560" height="315" src="https://www.youtube.com/embed/rINRnicv7_I?autoplay=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


<!--
How can quadrupeds walk over soft terrain?
We present STANCE which stands for Soft Terrain Adaptation and Compliance Estimation. 
STANCE is an online soft terrain adaptation algorithm that can adapt to any type of terrain compliance (stiff or soft). 
With STANCE, HyQ can adapt its locomotion strategy and walk over multiple terrains with different compliance without pre-tuning.

STANCE is now accepted at the IEEE Transactions on Robotics. 
- Updated preprint: https://lnkfi.re/STANCE_paper
- Blog: https://shamelfahmi.com/research/stance/
- The prequel of this work can be found in: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8678400
- For more information, visit the DLS lab website: https://dls.iit.it
-->