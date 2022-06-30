---
layout: page
title: Projects
permalink: /projects/
corl2022YoutubeID: lqzpASJkAVg
drakeYoutubeID: AOPWpT0N_g4
icra2021YoutubeID: YkFrG4_h6_k
andreasYoutubeID: y7z-Yn1PQNI
thaoYoutubeID: WMAdGhMmXEQ
---

A more complete list of my projects can be seen in my CV <a href="{% link /assets/files/corsaro_cv.pdf %}"> here</a>.

# Learning Task-Oriented Grasps from Limited Labeled Data

This work is currently under review at CoRL 2022. We propose a deep-learning-based method for detecting task-oriented grasps that leverages a pre-trained general grasp quality network branch to efficiently generalize to a new task within 10 to 20 training examples. A pre-print is available [upon request](mailto:matthew_corsaro@brown.edu).

{% include youtubePlayer.html id=page.corl2022YoutubeID %}

# Learning to Detect Multi-Modal Grasps for Dexterous Grasping in Dense Clutter

I presented [this paper](http://irl.cs.brown.edu/pubs/multimodal_grasps.pdf) at IROS 2021. See the blog post about it [here](https://mattcorsaro1.github.io/2021/09/29/multimodalgrasping.html) and the code [here](https://github.com/mattcorsaro1/MultiModalGrasping).

{% include youtubePlayer.html id=page.icra2021YoutubeID %}

# Drake Controller & Model: Robotiq 3-Finger Adaptive Gripper

My implementation of a hybrid controller for Robotiq's 3-Finger Adapative gripper is available [here](https://github.com/mattcorsaro1/drake/tree/robotiq_3f/examples/robotiq_3f). The underlying hybrid model is described in [Technical Report: Use of Hybrid Systems to Model the Robotiq Adaptive Gripper](https://www.researchgate.net/profile/Giulia_Franchi2/publication/278158284_Use_of_Hybrid_Systems_to_model_the_RobotiQ_Adaptive_Gripper/links/557ca3a708aec87640db4f0d/Use-of-Hybrid-Systems-to-model-the-RobotiQ-Adaptive-Gripper.pdf).

{% include youtubePlayer.html id=page.drakeYoutubeID %}

# Robot Object Retrieval with Contextual Natural Language Queries

This system enables a robot to request any object to complete a given task without explicitly classifying each available object. By providing a verb phrase such as "pass me something to cut with" rather than a noun phrase such as "pass me the scissors," the system implicitly learns objects' utilities and generalizes to novel objects.

{% include youtubePlayer.html id=page.thaoYoutubeID %}

Video credit: [Thao Nguyen](https://scholar.google.com/citations?user=XLo6c5EAAAAJ)

# Kuka iiwa Interface

[Ben Abbatematteo](https://babbatem.github.io/) and I developed the [kuka_brown repository](https://github.com/h2r/kuka_brown). kuka_brown contains all the code required to control our lab's Kuka LBR iiwa robot arm, Robotiq 3-Finger Adaptive Gripper, and various depth sensors.

# Grasp Pose Detection in Dense Clutter with a UR5

As a master's student at Northeastern, I ported [High Precision Grasp Pose Detection in Dense Clutter](https://ieeexplore.ieee.org/abstract/document/7759114) to our UR5 arm with a Robotiq parallel-jaw gripper and worked on various improvements to increase the grasp success rate.

{% include youtubePlayer.html id=page.andreasYoutubeID %}

Video credit: [Andreas ten Pas](https://www.ccs.neu.edu/home/atp/)
