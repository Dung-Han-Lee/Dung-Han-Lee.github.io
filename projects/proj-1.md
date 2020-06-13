---
layout: post
title: 'RIU-Net Row Detection for LIDAR-base navigation'
---

<img src="/assets/img/projects/proj-1/conversion.png" alt="conversion" class="responsive"/>

#### My Contribution Highlights
* Trained an [RIUNet](https://arxiv.org/abs/1905.08748) using Python and Pytorch, enabling LIDAR-based in-row navigation when GPS are not reliable enough
* Implemented data augmentation and weight-map to improve performance
* Implemented conversion between range-images and pointclouds, as well as their visualization functions

<img src="/assets/img/projects/proj-1/output.png" alt="output" class="responsive"/>

#### More About the Project
Inspired by my capstone project at Carnegie Mellon University, I conducted an independent study at Field Robotic Center under [George Kantor's](https://www.ri.cmu.edu/ri-faculty/george-a-kantor/) supervision. My role was to investigate pure LIDAR-based, in-row navigation for algricultural robots. I converted LIDAR data collected from field and manually labeled them into 150 training images, which were used to train an UNet model from scrath on AWS machine. As a result, the model achieved 0.79 IOU performance, and 
a 96% success rate on the two-line aligement test.

#### Source Code
Visit my [repository](https://github.com/Dung-Han-Lee/RIUNET-Row-Detection-with-LIDAR-range-image) for more technical details


