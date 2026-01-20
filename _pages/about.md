---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year Ph.D. student in **Mechanical Engineering** at UC Berkeley, where I am a member of the [Hybrid Robotics Group](https://hybrid-robotics.berkeley.edu/index.html) advised by [Prof. Koushil Sreenath](https://hybrid-robotics.berkeley.edu/koushil/). My research focuses on **Robotics**, **Reinforcement Learning (RL)** and **Generative Models**. Prior to Berkeley, I received my B.S. in Modern Mechanics from the [University of Science and Technology of China](https://en.ustc.edu.cn/) (USTC).

Publications
======

<style>
.pub-item {
  display: flex;
  flex-direction: row;
  gap: 24px;
  margin-bottom: 2rem;
  padding: 1.5rem;
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.06);
  border: 1px solid #efefef;
  transition: all 0.25s ease;
}

.pub-item:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 25px rgba(0,0,0,0.1);
}

.pub-media {
  flex: 0 0 320px;
  max-width: 100%;
}

.pub-media iframe {
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 8px;
  border: 1px solid #eee;
  display: block;
}

.pub-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
}

.pub-title {
  font-size: 1.15rem;
  font-weight: 700;
  margin-bottom: 0.6rem;
  line-height: 1.3;
}

.pub-title a {
  text-decoration: none;
  color: #222;
}

.pub-title a:hover {
  color: #52adc8;
  text-decoration: underline;
}

.pub-authors {
  font-size: 0.95rem;
  color: #444;
  margin-bottom: 0.6rem;
}

.pub-venue {
  font-style: italic;
  color: #666;
  margin-bottom: 1.2rem;
  font-size: 0.9rem;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: auto;
}

.pub-links a {
  display: inline-block;
  padding: 4px 14px;
  font-size: 0.85rem;
  font-weight: 600;
  text-decoration: none;
  color: #52adc8;
  border: 1px solid #52adc8;
  border-radius: 20px;
  transition: all 0.2s;
}

.pub-links a:hover {
  background: #52adc8;
  color: #fff !important;
  text-decoration: none;
}

@media (max-width: 850px) {
  .pub-item {
    flex-direction: column;
    padding: 1rem;
  }
  .pub-media {
    flex: 0 0 auto;
    width: 100%;
  }
}
</style>

<div class="pub-item">
  <div class="pub-media">
    <iframe src="https://www.youtube.com/embed/9AN0GulqWwc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="pub-content">
    <div class="pub-title">
      <a href="https://hybrid-robotics.berkeley.edu/langwbc/">LangWBC: Language-directed Humanoid Whole-Body Control via End-to-end Learning</a>
    </div>
    <div class="pub-authors">
      <strong>Yiyang Shao*</strong>, Xiaoyu Huang*, Bike Zhang, Qiayuan Liao, Yuman Gao, Yufeng Chi, Zhongyu Li, Sophia Shao, Koushil Sreenath
    </div>
    <div class="pub-venue">
      Robotics: Science and Systems (RSS), 2025
    </div>
    <div class="pub-links">
      <a href="https://www.roboticsproceedings.org/rss21/p065.pdf">Paper</a>
      <a href="https://arxiv.org/abs/2504.21738">arXiv</a>
      <a href="https://www.youtube.com/watch?v=9AN0GulqWwc">Video</a>
      <a href="https://hybrid-robotics.berkeley.edu/langwbc/">Project Page</a>
    </div>
  </div>
</div>


Prior Projects
======

Learning for Safe Multiple Heterogeneous Quadcopter Control via Generalizable Barrier Certificate
------
- Developed a heterogeneous safe controller for quadcopters with generalizable barrier certificate.
- Simultaneously learn the control barrier function and constrained control policy.
- Online system identification from observation history for heterogeneous adaptation.
<iframe width="560" height="315" src="https://www.youtube.com/embed/ymQ-hHWDRxs" title="Multi Quadcopter Safe Fly" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

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
