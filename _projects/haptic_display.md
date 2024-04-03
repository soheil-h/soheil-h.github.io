---
layout: page
title: Robot Learning With Haptic Displays
description: Wrapping haptic displays around robot arms to communicate learning
img: assets/img/projects/haptic_display/toh2023.jpg
importance: 3
category: PhD
---

Humans can leverage physical interaction to teach robot arms. As the human kinesthetically guides the robot through demonstrations, the robot learns the desired task. While prior works focus on how the robot learns, it is equally important for the human teacher to understand what their robot is learning. Visual displays can communicate this information; however, we hypothesize that visual feedback alone misses out on the <em>physical connection</em> between the human and robot. In this paper we introduce a novel class of <em>soft haptic displays</em> that wrap around the robot arm, adding signals without affecting interaction. We first design a pneumatic actuation array that remains flexible in mounting. We then develop single and multi-dimensional versions of this wrapped haptic display, and explore human perception of the rendered signals during psychophysic tests and robot learning.

<div class="row">
<div class="col-sm mt-3 mt-md-0">
{% include figure.liquid path="assets/img/projects/haptic_display/method.jpg" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
</div>
</div>
<div class="caption">
Experimental setup and independent variables for the user study. (Left) Participants physically demonstrated a mock welding task to a Franka Emika robot arm. We mounted two lasers to the robot's end-effector: the robot prompted human teachers to keep the end-effector and lasers at the correct distance, height, and orientation. (Right) The robot indicated which feature(s) it needed help with using three different feedback modalities: <b>GUI</b>, <b>Local</b>, and <b>Global</b>.
</div>

We ultimately find that people <em>accurately distinguish</em> single-dimensional feedback with a Weber fraction of 11.4%, and identify multi-dimensional feedback with 94.5% accuracy. When physically teaching robot arms, humans leverage the single- and multi-dimensional feedback to provide better demonstrations than with visual feedback: our wrapped haptic display decreases teaching time while increasing demonstration quality. This improvement depends on the location and distribution of the wrapped haptic display.


<p align="center"><iframe width="560" height="315" src="https://www.youtube.com/embed/yPcMGeqsjdM?rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>
