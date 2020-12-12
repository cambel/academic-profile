---
title: Learning to graps with primitive-shaped objects
summary: Learning to grasp using Baxter with joint torque control.
tags:
- Deep Learning
- Grasping
- Robot learning
- Model-based reinforcement learning
date: "2018-01-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "Proposed Framework"
  focal_point: ""

links:
url_code: ""
url_pdf: https://ieeexplore.ieee.org/document/8700399
url_slides: ""
url_video: ""

---
Training Baxter to grasp objects based on vision feedback and joint-torque control.

**Reinforcement Learning algorithm:** [Guided Policy Search](https://github.com/cbfinn/gps).

The environment is simulated using Gazebo/ROS Kinetic.

## Training session
![gif](./training-baxter.gif)

## Learned policy
![gif](./trained-baxter.gif)

