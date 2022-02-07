---
title: "Research"
permalink: /research/
header:
classes: wide
mathjax: "true"
---
These are some pointers to my current research interests. 
Click "[read more]()" for more information on every topic.

## ViTAL: Vision-Based Terrain-Aware Locomotion for Legged Robots (:collision:coming soon:collision:)
<center>
<img src="https://drive.google.com/uc?id=1Xe_jZ8zpLTfhVGVhx7LN7HX7YkZgpeH8"
     alt="Markdown Monster icon"
     style="height: 220px;
     margin-bottom: 20px;" />
</center>

Common strategies in vision-based planning for legged robots separate locomotion planning into foothold selection and pose adaptation.
Current pose adaptation strategies optimize the robot’s body pose relative to given footholds. 
If these footholds are not reached, the robot may end up in a state with no reachable safe footholds. 
To solve this, we present a Vision-Based Terrain-Aware Locomotion (ViTAL) strategy.
ViTAL has novel pose adaptation and foothold selection algorithms. 
ViTAL introduces a different paradigm in pose adaptation that does not optimize the body pose relative to given footholds, but the body pose that maximizes the chances of the legs in reaching safe footholds.
ViTAL plans footholds and poses based on skills that characterize the capabilities of the robot and its legs, and the robot’s terrain-awareness. 

## Locomotion Adaptation for Legged Robots over Soft Terrain

<center>
<img src="https://drive.google.com/uc?id=1VOqm5zE6TSEIM_lsqS6ZJ5j4lnE6u5PY"
     alt="Markdown Monster icon"
     style="height: 300px;
     margin-bottom: 20px;" />
</center>

Whole-body Control (WBC) can achieve multiple locomotion tasks while respecting the robot’s dynamics. However, most of WBC frameworks fail to generalize beyond rigid terrains. Over soft terrain, the stability and performance of the legged robot deteriorate if the WBC is not accounting for the introduced uncertainty due to the soft contact interaction.  To deal with this, we propose a novel soft terrain adaptation algorithm called STANCE: Soft Terrain Adaptation and Compliance Estimation. STANCE consists of a WBC that exploits the knowledge of the terrain to generate an optimal solution that is contact consistent and an online terrain compliance estimator that provides the WBC with terrain knowledge. 
[read more]({% link _research/stance.md %})


## Whole-Body Control for Legged Robots
<center>
<img src="https://drive.google.com/uc?id=1ARu9dOQ2Ti7sFnmTq8ZEWV3JYeBysF1o"
     alt="Markdown Monster icon"
     style="height: 300px;
     margin-bottom: 20px;" />
</center>

For dynamic locomotion, it is essential to reason about the robot’s dynamics, actuation limits and interaction with the environment. To do so, we exploit optimization techniques in locomotion control to formulate a Whole-Body Control (WBC) framework. WBC is a motion tracking controller capable of achieving multiple locomotion tasks while respecting the robot’s behavior. 
[read more]({% link _research/wbc.md %})

---
<!--
https://drive.google.com/uc?export=view&id=
-->
