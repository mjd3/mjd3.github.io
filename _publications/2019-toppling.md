---
title: 'Robust Toppling for Vacuum Suction Grasping'
authors: 'Christopher Correa, Jeffrey Mahler, Michael Danielczuk, Ken Goldberg'
venue: 'IEEE International Conference on Automation Science and Engineering (CASE)'
date: 2019-08-22
category: 'published'
pdf: '2019-toppling.pdf'
teaser: '2019-toppling.png'
bibtex: '2019-toppling.bib'
permalink: /publications/2019-toppling
collection: publications
---

Abstract
-------
When robust vacuum suction grasps are not accessible, toppling can change an object’s 3D pose to provide access to suction grasps. We extend prior toppling models by characterizing the robustness of toppling a 3D object specified by a triangular mesh, using Monte Carlo sampling to account for uncertainty in pose, friction coefficients, and push direction. The model estimates the resulting distribution of object poses following a topple action. We run 700 physical toppling experiments using an ABB YuMi and find that the model outperforms a baseline model by an absolute 26.9% when comparing the total variation distance between each model’s predicted probability distribution and the empirical distribution. We use the robust model as the state transition function in a Markov Decision Process (MDP) to plan optimal sequences of toppling actions to expose access to robust suction grasps. Data from 20,000 simulated rollouts suggest the policy can increase suction grasp reliability by 33.6%, computed using grasp analysis from the Dexterity Network (Dex-Net) 3.0. We generate a dataset of the predicted reliability of toppling at 1,257,000 candidate points on 189 3D meshes. Code and datasets can be found [here](https://sites.google.com/view/toppling).
