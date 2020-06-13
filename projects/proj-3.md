---
layout: post
title: 'ShellNet Row Detection for LIDAR-base navigation'
---

<img src="/assets/img/projects/proj-3/thumb.jpg" alt="architecture" class="responsive"/>

#### My Contribution Highlights
* Transformed ShellNet from authors TensorFlow implementation to Python code using Pytorch running on CPU, enabling LIDAR-base navigation with pointcloud as input
* Implemented ROS integration code for easy robot integration

<img src="/assets/img/projects/proj-3/output.png" alt="output" class="responsive"/>

#### More About the Project
Inspired by my capstone project at Carnegie Mellon University, I conducted an independent study at Field Robotic Center under [George Kantor's](https://www.ri.cmu.edu/ri-faculty/george-a-kantor/) supervision. My role was to investigate pure LIDAR-based, in-row navigation for algricultural robots. I labeled 150 LIDAR pointcloud data into training data, which were used to train an ShellNet model from scrath on AWS machine. As a result, the model achieved 0.75 IOU performance.

#### Source Code
Visit my [repository](https://github.com/Dung-Han-Lee/Pointcloud-based-Row-Detection-using-ShellNet-and-PyTorch) for more technical details
