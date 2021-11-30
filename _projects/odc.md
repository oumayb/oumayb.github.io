---
layout: page
title: Online Learning and Control of Dynamical Systems from Sensory Input
description: Oumayma Bounou, Jean Ponce, Justin Carpentier
#img: assets/img/12.jpg
importance: 1
category: work
---

---------------
#### Abstract
Identifying an effective model of a dynamical system from sensory data and using it for future state prediction and control is challenging. Recent data-driven algorithms based on Koopman theory are a promising approach to this problem, but they typically never update the model once it has been identified from a relatively small set of observations, thus making long-term prediction and control difficult for realistic systems, in robotics or fluid mechanics for example. This paper introduces a novel method for learning an embedding of the state space with linear dynamics from sensory data. Unlike previous approaches, the dynamics model can be updated online and thus easily applied to systems with non-linear dynamics in the original configuration space. The proposed approach is evaluated empirically on several classical dynamical systems and sensory modalities, with good performance on long-term prediction and control.


<center><div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-3">
        {% responsive_image path: assets/img/simple.gif title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-3">
        {% responsive_image path: assets/img/double.gif title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-3">
        {% responsive_image path: assets/img/cartpole.gif title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div></center>
<div class="caption">
    Left: Pendulum. Middle: Double pendulum. Right: Cartpole system.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/approach_offline.png title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Approach.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/approach_online.png title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Online update.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/simple.jpg title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Impact of online updates on the quality of the prediction for the pendulum.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/double.jpg title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Impact of online updates on the quality of the prediction for the double pendulum.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/cartpole.jpg title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Impact of online updates on the quality of the prediction for the cartpole system.
</div>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/fig_control.png title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The goal is to take the cartpole system from an initial position specified with the left-most images (red) to a target position specified with the right-most image (green).
</div>

 <center><div class="row justify-content-sm-center">
    <center><div class="col-sm mt-3 mt-md-0">
        {% responsive_image path: assets/img/fig_control_2.png title: "example image" class: "img-fluid rounded z-depth-1" %}
    </div></center>
</div> </center>
<div class="caption">
    Generated controlled sequence.
</div>

