---
layout: page
title: Transparent Robot Learning
description: Robots reveal reward learning when asking questions
img: assets/img/projects/reward_learning/thri2022.jpg
importance: 6
category: PhD
---

Robots can learn from humans by asking questions. In these questions the robot demonstrates a few different behaviors and asks the human for their favorite. But how should robots choose which questions to ask? Today’s robots optimize for <em>informative</em> questions that actively probe the human’s preferences as efficiently as possible. But while informative questions make sense from the robot’s perspective, human onlookers may find them arbitrary and <em>misleading</em>. For example, consider an assistive robot learning to put away the dishes. Based on your answers to previous questions this robot knows where it should stack each dish; however, the robot is unsure about right height to carry these dishes. A robot optimizing only for informative questions focuses purely on this height: it shows trajectories that carry the plates near or far from the table, regardless of whether or not they stack the dishes correctly. As a result, when we see this question, we mistakenly think that the robot is still confused about where to stack the dishes! We formalize active preference-based learning from the human’s perspective.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/projects/reward_learning/thri_1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    A robot asking multiple-choice questions to learn the human’s reward function.
</div>

We hypothesize that — from the human’s point-of-view — the robot’s questions reveal what the robot has and has not learned. Our insight enables robots to use questions to make their learning process <em>transparent</em> to the human operator. We develop and test a model that robots can leverage to relate the questions they ask to the information these questions reveal. We then introduce a trade-off between informative and revealing questions that considers both human and robot perspectives: a robot that optimizes for this trade-off actively gathers information from the human while simultaneously keeping the human up to date with what it has learned. We evaluate our approach across simulations, online surveys, and in-person user studies. We find that robots which consider the human’s point of view learn just as quickly as state-of-the-art baselines while also communicating what they have learned to the human operator.



<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/tC6y_jHN7Vw?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
