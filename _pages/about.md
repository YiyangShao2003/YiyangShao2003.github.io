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
  margin-bottom: 1.5rem;
  padding: 1.25rem;
  background: #ffffff;
  border-radius: 10px;
  border: 1px solid #e8e8e8;
}

.pub-item:hover {
  border-color: #52adc8;
}

.pub-media {
  flex: 0 0 300px;
  max-width: 100%;
}

.pub-media iframe {
  width: 100%;
  aspect-ratio: 16 / 9;
  border-radius: 6px;
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
  font-size: 1.1rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
  line-height: 1.35;
}

.pub-title a {
  text-decoration: none;
  color: #222;
}

.pub-title a:hover {
  color: #52adc8;
}

.pub-authors {
  font-size: 0.9rem;
  color: #555;
  margin-bottom: 0.4rem;
}

.pub-venue {
  font-style: italic;
  color: #777;
  margin-bottom: 0.8rem;
  font-size: 0.85rem;
}

.pub-desc {
  font-size: 0.9rem;
  color: #444;
  margin-bottom: 0.8rem;
  line-height: 1.5;
}

.pub-desc ul {
  margin: 0;
  padding-left: 1.2rem;
}

.pub-desc li {
  margin-bottom: 0.25rem;
}

.pub-links {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: auto;
}

.pub-links a {
  display: inline-block;
  padding: 4px 12px;
  font-size: 0.8rem;
  font-weight: 600;
  text-decoration: none;
  color: #52adc8;
  border: 1px solid #52adc8;
  border-radius: 16px;
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

<div class="pub-item">
  <div class="pub-media">
    <iframe src="https://www.youtube.com/embed/ymQ-hHWDRxs" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="pub-content">
    <div class="pub-title">Learning for Safe Multiple Heterogeneous Quadcopter Control via Generalizable Barrier Certificate</div>
    <div class="pub-desc">
      <ul>
        <li>Developed a heterogeneous safe controller for quadcopters with generalizable barrier certificate.</li>
        <li>Simultaneously learn the control barrier function and constrained control policy.</li>
        <li>Online system identification from observation history for heterogeneous adaptation.</li>
      </ul>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-media">
    <iframe src="https://www.youtube.com/embed/7xYu7EeKpm8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="pub-content">
    <div class="pub-title">Geometry Variation Model Predictive Control For Bipedal Robot</div>
    <div class="pub-desc">
      <ul>
        <li>Geometry representation of system dynamic, invariant to coordinate system and free from singularity.</li>
        <li>Variation-based linearization of system dynamic to ensure the discretized system is energy-conserving.</li>
        <li>Enable stable walking of a bipedal robot via convex MPC.</li>
      </ul>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-media">
    <iframe src="https://www.youtube.com/embed/DIakTY5WKMU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="pub-content">
    <div class="pub-title">State Estimation and Control of a Wheeled-Bipedal Robot</div>
    <div class="pub-desc">
      <ul>
        <li>Developed a robust state estimation and high-performance control algorithm for a wheeled-bipedal robot.</li>
        <li>Detect slipping based on the velocity difference of wheels' contact points with the ground in the inertial frame.</li>
        <li>Designed LQR controller based on whole-body dynamics.</li>
      </ul>
    </div>
    <div class="pub-links">
      <a href="https://yiyangshao2003.github.io/files/Bipedal.pdf">Details</a>
    </div>
  </div>
</div>

<div class="pub-item">
  <div class="pub-media">
    <iframe src="https://www.youtube.com/embed/DtH-J36skYA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
  <div class="pub-content">
    <div class="pub-title">SLAM and Navigation of an Omnidirectional Robot</div>
    <div class="pub-desc">
      <ul>
        <li>Develop a navigation system for a mobile robot to navigate through uneven terrain.</li>
        <li>Enhance localization frequency and accuracy by integrating lidar, IMU, and encoder data using a Kalman filter.</li>
        <li>Analyze terrain traversability through point cloud segmentation.</li>
      </ul>
    </div>
    <div class="pub-links">
      <a href="https://kevin-shao-ustc.github.io/Sentry.pdf">Details</a>
    </div>
  </div>
</div>
