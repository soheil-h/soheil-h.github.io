---
layout: page
title: Waypoint Learning
description: Waypoint-Based RL for Robot Manipulation Tasks
img: assets/img/projects/waypoint_learning/iros2024.jpg
importance: 1
category: PhD
---

Robot arms should be able to learn new tasks. One framework here is reinforcement learning, where the robot is given a reward function that encodes the task, and the robot autonomously learns actions to maximize its reward. Existing approaches to reinforcement learning often frame this problem as a Markov decision process, and learn a policy (or a hierarchy of policies) to complete the task. These policies reason over hundreds of fine-grained actions that the robot arm needs to take: e.g., moving slightly to the right or rotating the end-effector a few degrees.
But the manipulation tasks that we want robots to perform can often be broken down into a small number of high-level motions: e.g., reaching an object or turning a handle. In this paper we therefore propose a <em>waypoint-based</em> approach for model-free reinforcement learning. Instead of learning a low-level policy, the robot now learns a trajectory of waypoints, and then interpolates between those waypoints using existing controllers.

<div class="container" style="text-align: center;">
    {% include figure.liquid path="assets/img/projects/waypoint_learning/method.jpg"  class="img-fluid rounded z-depth-1" zoomable=false width="60%" height="auto" %}
</div>
<div class="caption">
Our waypoint-based approach for model-free reinforcement learning in manipulation tasks. The robot arm learns where to place the next waypoint to maximize its reward by solving a multi-armed bandit. 
</div>


Our key novelty is framing this waypoint-based setting as a sequence of multi-armed bandits: each bandit problem corresponds to one waypoint along the robot's motion. We theoretically show that an ideal solution to this reformulation has lower regret bounds than standard frameworks. We also introduce an approximate posterior sampling solution that builds the robot's motion one waypoint at a time. Results across benchmark simulations and two real-world experiments suggest that this proposed approach learns new tasks more quickly than state-of-the-art baselines. 

<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/MMEd-lYfq4Y?si=D3fx8Dg-gfrVsPOs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>