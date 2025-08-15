---
title: Offline Reinforcement Learning Strategy for Floor Cleaning Robots Based on Conservative Q-Learning Algorithm
date: 2023-02-01
tags:
  - Reinforcement Learning
  - ROS
  - Robotics
  - Machine Learning
---

**Project Duration:** Sep. 2022 to Feb. 2023

## Project Details

1. Within the ROS environment based on the Noetic version, an offline reinforcement learning algorithm CQL (Conservative Q-Learning) is utilized, introducing conservative constraints into the Q-value updates
2. Various domestic simulation environments are constructed in Gazebo, and path trajectories are generated using the A* algorithm to collect trajectory data
3. The Rviz tool is employed to view and analyze the robot's trajectory, with manual annotation of the optimal path
4. The annotated data serves as a supervisory signal to train the model, with the parameters being saved

## Achievements

A simulation path training set for the vacuum cleaner in Gazebo has been obtained. The conservative coefficient α has been adjusted to optimize the CQL (Conservative Q-Learning) model.

<!--more-->
