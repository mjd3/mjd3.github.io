---
title: 'Segmenting Unknown 3D Objects from Real Depth Images using Mask R-CNN Trained on Synthetic Data'
authors: 'Michael Danielczuk, Matthew Matl, Saurabh Gupta, Andrew Li, Andrew Lee, Jeffrey Mahler, Ken Goldberg'
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
date: 2019-05-20
category: 'published'
pdf: '2019-sdmaskrcnn.pdf'
teaser: '2019-sdmaskrcnn.png'
bibtex: '2019-sdmaskrcnn.bib'
permalink: /publication/2019-sdmaskrcnn
collection: publications
---

Abstract
-------
The ability to segment unknown objects in depth images has potential to enhance robot skills in grasping and object tracking. Recent computer vision research has demonstrated that Mask R-CNN can be trained to segment specific categories of objects in RGB images when massive hand-labeled datasets are available. As generating these datasets is time-consuming, we instead train with synthetic depth images. Many robots now use depth sensors, and recent results suggest training on synthetic depth data can transfer successfully to the real world. We present a method for automated dataset
generation and rapidly generate a synthetic training dataset of 50,000 depth images and 320,000 object masks using simulated heaps of 3D CAD models. We train a variant of Mask R-CNN with domain randomization on the generated dataset to perform category-agnostic instance segmentation without any hand-labeled data and we evaluate the trained network, which we refer to as Synthetic Depth (SD) Mask R-CNN, on a set of real, high-resolution depth images of challenging, densely-cluttered bins containing objects with highly-varied geometry. SD Mask R-CNN outperforms point cloud clustering baselines by an absolute 15% in Average Precision and 20% in Average Recall on COCO benchmarks, and achieves performance levels similar to
a Mask R-CNN trained on a massive, hand-labeled RGB dataset and fine-tuned on real images from the experimental setup. We deploy the model in an instance-specific grasping pipeline to demonstrate its usefulness in a robotics application. Code, datasets, models, and supplementary material are available [here](https://bit.ly/2letCuE).
