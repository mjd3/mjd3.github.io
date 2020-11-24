---
title: 'Object Rearrangement Using Learned Implicit Collision Functions'
authors: '**Michael Danielczuk\***, Arsalan Mousavian*, Clemens Eppner, Dieter Fox'
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
date: 2020-10-31
category: 'submitted'
type: 'preprint'
pdf: https://arxiv.org/pdf/2011.10726.pdf
video: https://youtu.be/TttnZCF5ppQ
website: https://sites.google.com/nvidia.com/scenecollisionnet
teaser: '2020-rearrangement.png'
bibtex: '2020-rearrangement.bib'
permalink: /publications/2020-rearrangement
collection: publications
---

Abstract
-------
Robotic object rearrangement combines the skills of picking and placing objects. When object models are unavailable, typical collision-checking models may be unable to predict collisions in partial point clouds with occlusions, making generation of collision-free grasping or placement trajectories challenging. We propose a learned collision model that accepts scene and query object point clouds and predicts collisions for 6DOF object poses within the scene. We train the model on a synthetic set of 1 million scene/object point cloud pairs and 2 billion collision queries. We leverage the learned collision model as part of a model predictive path integral (MPPI) policy in a tabletop rearrangement task and show that the policy can plan collision-free grasps and placements for objects unseen in training in both simulated and physical cluttered scenes with a Franka Panda robot. The learned model outperforms both traditional pipelines and learned ablations by 9.8% in accuracy on a dataset of simulated collision queries and is 75x faster than the best-performing baseline. Videos and supplementarymaterial are available at [https://sites.google.com/nvidia.com/scenecollisionnet](https://sites.google.com/nvidia.com/scenecollisionnet).
