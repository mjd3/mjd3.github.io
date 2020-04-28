---
title: 'Minimal Work: A Grasp Quality Metric for Deformable Hollow Objects'
authors: 'Jingyi Xu, Michael Danielczuk, Jeff Ichnowski, Jeffrey Mahler, Eckehard Steinbach, Ken Goldberg'
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
date: 2020-03-01
category: 'accepted'
pdf: '2020-min-work.pdf'
teaser: '2020-min-work.png'
bibtex: '2020-min-work.bib'
permalink: /publications/2020-min-work
collection: publications
---

Abstract
-------
Robot grasping of deformable hollow objects such as plastic bottles and cups is challenging as the grasp should resist disturbances while minimally deforming the object so as not to damage it or dislodge liquids. We propose minimal work as a novel grasp quality metric that combines wrench resistance and the object deformation. We introduce an efficient algorithm to compute required work to resist an external wrench for a manipulation task by solving a linear program. The algorithm first computes the minimum required grasp force and an estimation of the gripper jaw displacements based on the object deformability at different locations measured with physical experiments. The work done by the jaws is the product of the grasp force and the displacements. The grasp quality metric is computed based on the required work under perturbations of grasp poses to address uncertainties in actuation. We collect 460 physical grasps with a UR5 robot and a Robotiq gripper. Physical experiments suggest the minimal work quality metric reaches 74.2% balanced accuracy and is up to 24.2% higher than classical wrench-based quality metrics, where the balanced accuracy is the raw accuracy normalized by the number of successful and failed real-world grasps.
