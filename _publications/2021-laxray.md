---
title: 'Mechanical Search on Shelves using Lateral Access X-RAY'
authors: 'Huang Huang\*, Marcus Dominguez-Kuhne\*, Jeffrey Ichnowski, Vishal Satish, **Michael Danielczuk** , Kate Sanders, Andrew Lee, Anelia Angelova, Vincent Vanhoucke, Ken Goldberg'
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
date: 2021-06-30
category: 'accepted'
type: 'conference'
pdf: https://arxiv.org/pdf/2011.11696.pdf
video: https://youtu.be/0xWzh9bBLeU
website: https://sites.google.com/berkeley.edu/lax-ray/home
teaser: '2021-laxray.png'
bibtex: '2021-laxray.bib'
permalink: /publications/2021-laxray
collection: publications
---

Abstract
-------
Efficiently finding an occluded object with lateral access arises in many contexts such as warehouses, retail, healthcare, shipping, and homes. We introduce LAX-RAY (Lateral Access maXimal Reduction of occupancY support Area), a system to automate the mechanical search for occluded objects on shelves. For such lateral access environments, LAX-RAY couples a perception pipeline predicting a target object occupancy support distribution with a mechanical search policy that sequentially selects occluding objects to push to the side to reveal the target as efficiently as possible. Within the context of extruded polygonal objects and a stationary target with a known aspect ratio, we explore three lateral access search policies: Distribution Area Reduction (DAR), Distribution Entropy Reduction (DER), and Distribution Entropy Reduction over Multiple Time Steps (DER-MT) utilizing the support distribution and prior information. We evaluate these policies using the First-Order Shelf Simulator (FOSS) in which we simulate 800 random shelf environments of varying difficulty, and in a physical shelf environment with a Fetch robot and an embedded PrimeSense RGBD Camera. Average simulation results of 87.3% success rate demonstrate better performance of DER-MT with 2 prediction steps. When deployed on the robot, results show a success rate of at least 80% for all policies, suggesting that LAX-RAY can efficiently reveal the target object in reality. Both results show significantly better performance of the three proposed policies compared to a baseline policy with uniform probability distribution assumption in non-trivial cases, showing the importance of distribution prediction. Code, videos, and supplementary material can be found at [https://sites.google.com/berkeley.edu/lax-ray](https://sites.google.com/berkeley.edu/lax-ray).
