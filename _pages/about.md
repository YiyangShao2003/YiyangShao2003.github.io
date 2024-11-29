---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fourth-year undergraduate student in [University of Science and Technology of China](https://en.ustc.edu.cn/).  I am currently visiting [UC Berkeley, Hybrid Robotics Group](https://hybrid-robotics.berkeley.edu/index.html), under the supervision of Prof. [Koushil Sreenath](https://hybrid-robotics.berkeley.edu/koushil/). Before that, I was supervised by Prof. [Shiwu Zhang](https://scholar.google.com.hk/citations?user=d6tBg_UAAAAJ&hl=en-EN) at USTC. 
I am looking for a PhD position this application season!

Research Interests
======
My interest lies in **Control** and **Robot Learning**. I am currently focused on bridging high-level intelligence with low-level controller in physical world. 

Research Experience
======

Humanoid Whole Body Control Via Text Command
------
- Developed a whole body controller for a humanoid robot through text command, based on the teacher-student framework.
- Teacher policies are trained using reinforcement learning to track captioned reference motion from HumanML3D.
- A text-conditioned student policy is then distilled from the teacher policies using behavior cloning and finetuned through reinforcement learning to transit between motions.
- The result policy demonstrates capability to perform sequential motions based on text commands.
<iframe width="560" height="315" src="https://www.youtube.com/embed/aMt2kglz3cg" title="Humanoid Whole Body Control Via Text Command" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Learning for Safe Multiple Heterogeneous Quadcopter Control via Generalizable Barrier Certificate
------
- Developed a heterogeneous safe controller for quadcopters with generalizable barrier certificate.
- Simultaneously learn the control barrier function and constrained control policy.
- Online system identification from observation history for heterogeneous adaptation.
<iframe width="560" height="315" src="https://www.youtube.com/embed/8XGncoPI3bc" title="Multi Quadcopter Safe Fly" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Geometry Variation Model Predictive Control For Bipedal Robot
------
- Geometry representation of system dynamic, invariant to coordinate system and free from singularity.
- Variation-based linearization of system dynamic to ensure the discretized system is energy-conserving.
- Enable stable walking of a bipedal robot.
Convex MPC based on geometry representation of system dynamics. Free of singularity and energy preserving.  
<iframe width="560" height="315" src="https://www.youtube.com/embed/7xYu7EeKpm8" title="Multi Quadcopter Safe Fly" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

State Estimation and Control of a Wheeled-Bipedal Robot
------
- Developed a robust state estimation and high-performance control algorithm for a wheeled-bipedal robot.
- Detect slipping based on the velocity difference of wheels' contact points with the ground in the inertial frame to adjust covariance in state estimation Kalman filter.
- Designed LQR controller based on whole-body dynamics.
- More details can be found [HERE](https://yiyangshao2003.github.io/files/Bipedal.pdf)
<iframe width="560" height="315" src="https://www.youtube.com/embed/DIakTY5WKMU" title="Wheeled-Bipedal Robot" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

SLAM and Navigation of an Omnidirectional Robot
------ 
- Develop a navigation system for a mobile robot to navigate through uneven terrain.
- Enhance localization frequency and accuracy by integrating lidar, IMU, and encoder data using a Kalman filter.
- Analyze terrain traversability through point cloud segmentation.
- More details can be found [HERE](https://kevin-shao-ustc.github.io/Sentry.pdf)
<iframe width="560" height="315" src="https://www.youtube.com/embed/DtH-J36skYA" title="Slam and Navigation" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
