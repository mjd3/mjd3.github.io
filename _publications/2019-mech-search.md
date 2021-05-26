---
title: 'Mechanical Search: Multi-Step Retrieval of a Target Object Occluded by Clutter'
authors: '**Michael Danielczuk\***, Andrey Kurenkov\*, Ashwin Balakrishna, Matthew Matl, David Wang, Roberto Martín-Martín, Animesh Garg, Silvio Savarese,Ken Goldberg'
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
date: 2019-05-20
category: 'published'
type: 'conference'
pdf: https://arxiv.org/pdf/1903.01588.pdf
website: http://ai.stanford.edu/mech-search/
video: https://youtu.be/lCwdGSDkbG4
teaser: '2019-mech-search.png'
bibtex: '2019-mech-search.bib'
permalink: /publications/2019-mech-search
collection: publications
---

Abstract
-------
When operating in unstructured environments such as warehouses, homes, and retail centers, robots are frequently required to interactively search for and retrieve specific objects from cluttered bins, shelves, or tables. Mechanical Search describes the class of tasks where the goal is to locate and extract a known target object. In this paper, we formalize Mechanical Search and study a version where distractor objects are heaped over the target object in a bin. The robot uses an RGBD perception system and control policies to iteratively select, parameterize, and perform one of 3 actions
– push, suction, grasp – until the target object is extracted, or either a time limit is exceeded, or no high confidence push or grasp is available. We present a study of 5 algorithmic policies for mechanical search, with 15,000 simulated trials and 300 physical trials for heaps ranging from 10 to 20 objects. Results suggest that success can be achieved in this long-horizon task with algorithmic policies in over 95% of instances and that the
number of actions required scales approximately linearly with the size of the heap. Code and supplementary material can be found [here](http://ai.stanford.edu/mech-search).
