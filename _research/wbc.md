---
title: "Whole-body Control for Quadruped Robots"
collection: research
---

<img src="https://drive.google.com/uc?export=view&id=1R_OJuz8FwT9SYesOWamXTLR5WdYxyOyK"
     alt="Markdown Monster icon"
     />

## Overview
Our goal is to achieve dynamic locomotion over challenging unstructured terrain. This requires reasoning about the robot’s dynamics, actuation limits and interaction with the environment. To do so, we exploit optimization techniques in locomotion control to formulate a Whole-Body Control **(WBC)**.

**WBC** is a motion tracking controller that is capable of achieving multiple locomotion tasks while respecting the robot’s behavior. 
**WBC** casts locomotion control as an optimization problem, in which, by incorporating the full dynamics of the legged robot, all of its Degrees of Freedom (DoFs) are exploited in order to spread the desired motion tasks to all the joints. This allows us to reason  about multiple tasks and solve them in an optimization fashion while respecting the full system dynamics and the actuation and interaction constraints.


Our **WBC** was tested on **HyQ** over a wide range of challenging terrain (slopes, gaps, stairs, etc.), using
different gaits (crawl and trot). Our **WBC** is robust against inaccurate friction coefficient estimation and  unstable footholds.


## Selected publication(s): 
> [__Passive Whole-Body Control for Quadruped Robots: Experimental Validation Over Challenging Terrain.__](https://iit-dlslab.github.io/papers/fahmi19ral.pdf) <br>
Shamel Fahmi, Carlos Mastalli, Michele Focchi and Claudio Semini <br>
IEEE Robotics and Automation Letters (RA-L), 2019


## Contact: 
Shamel Fahmi and Michele Focchi

## Media:

<iframe width="560" height="315" src="https://www.youtube.com/embed/Lg3V_juoE1w?autoplay=0&mute=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
