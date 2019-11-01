---
title: 'REACH: Reducing False Negatives in Robot Grasp Planning with a Robust Efficient Area Contact Hypothesis Model'
authors: 'Michael Danielczuk, Jingyi Xu, Jeffrey Mahler, Matthew Matl, Nuttapong Chentanez, Ken Goldberg'
venue: 'International Symposium on Robotics Research (ISRR)'
date: 2019-10-07
category: 'published'
pdf: '2019-reach.pdf'
teaser: '2019-reach.png'
bibtex: '2019-reach.bib'
permalink: /publication/2019-reach
collection: publications
---

Abstract
-------
Although point contact models are ubiquitous for robot grasp planning, they do not model the range of wrenches that finite-area soft contacts provide. This approximation leads to many false negatives. To reduce these, we propose REACH, a Robust Efficient Area Contact Hypothesis model. We consider its potential benefits and investigate two potential drawbacks: increased computational complexity and increased false positives. The REACH model computes the contact profile using constructive solid geometry intersection and barycentric integration and estimates the contact’s ability to resist external wrenches (eg, gravity) under perturbations in object pose and material properties. We evaluate the performance of REACH with 2,625 physical grasps of 21 diverse objects with an ABB YuMi robot. We compare performance of a soft point contact model, an elliptical area contact model, and a rigid-body dynamic simulation model using NVIDIA Flex. The REACH model reduces false negatives by 17% compared to the point contact model, achieving 72% average recall. The REACH model also compares favorably to full dynamic simulation in Flex and is two orders of magnitude faster, with 50 ms average computation time. Experimental data and supplementary material are available [here](https://sites.google.com/berkeley.edu/reach).
