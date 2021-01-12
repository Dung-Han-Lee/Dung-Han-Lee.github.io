---
layout: post
title: "Triangulation"
---

### Least Square Estimation
Due to the presence of noise, the connection line between center of camera (O1, O2) and pixel point (p1, p2) will mostly not intersect. Therefore, the solution is to estimate the 3d point using least-square methods (SVD) assuming noise distribution is gaussian.

<img src="/assets/img/posts/triangulation_00.png" alt="conversion" class="responsive"/>

Specifically, given a pair of matching pixels and the two associated 3x4 projection matrices, 4 constraints can be established. Thus, a 4x4 matrix A can be established, whose eigenvector corresponding to the least eigen value is used as a least square solution.

<img src="/assets/img/posts/triangulation_01.png" alt="conversion" class="responsive"/>


### Stereo Camera
Monocular camera solution has scale ambiguity issues, thus stereo camera of known baseline could serve straight-forward point estimation. However, such camera has their own limitations such as minimum distance, and limited working distance. 


