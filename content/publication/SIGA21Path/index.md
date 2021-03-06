---
abstract: "We introduce the first path-oriented drone trajectory planning
  algorithm, which performs continuous (i.e., dense) image acquisition along an
  aerial path and explicitly factors path quality into an optimization along
  with scene reconstruction quality. Specifically, our method takes as input a
  rough 3D scene proxy and produces a drone trajectory and image capturing
  setup, which efficiently yields a high-quality reconstruction of the 3D scene
  based on three optimization objectives: one to maximize the amount of 3D scene
  information that can be acquired along the entirety of the trajectory, another
  to optimize the scene capturing efficiency by maximizing the scene information
  that can be acquired per unit length along the aerial path, and the last one
  to minimize the total turning angles along the aerial path, so as to reduce
  the number of sharp turns. Our search scheme is based on the rapidly-exploring
  random tree framework, resulting in a final trajectory as a single path
  through the search tree. Unlike state-of-the-art works, our joint optimization
  for view selection and path planning is performed in a single step. We
  comprehensively evaluate our method not only on benchmark virtual datasets as
  in existing works but also on several large-scale real urban scenes. We
  demonstrate that the continuous paths optimized by our method can effectively
  reduce onsite acquisition cost using drones, while achieving high-fidelity 3D
  reconstruction, compared to existing planning methods and oblique photography,
  a mature and popular industry solution."
slides: ""
url_pdf: "DronePath.pdf"
publication_types:
  - "1"
authors:
  - "*Admin*"
  - Yucong Yao
  - Ke Xie
  - Chi-Wing Fu
  - Hao Zhang
  - Hui Huang
author_notes: []
publication: "*Siggraph Asia 2021*"
summary: "We introduce the first path-oriented drone trajectory planning
  algorithm, which performs continuous (i.e., dense) image acquisition along an
  aerial path and explicitly factors path quality into an optimization along
  with scene reconstruction quality. "
url_dataset: ""
url_project: ""
publication_short: "*SIGA21*"
url_source: ""
url_video: "https://youtu.be/fFCgqmtM3kQ"
title: Continuous Aerial Path Planning for 3D Urban Scene Reconstruction
subtitle: ""
doi: ""
featured: true
tags: []
projects:
  - Reconstruction
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: teaser_single_s.jpg
date: 2021-09-02T10:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

You can watch the [demo](https://youtu.be/fFCgqmtM3kQ) and find the [supplementary](SIGA21Path_supp.pdf) here. This project can also be found via [this page](https://vcc.tech/research/2021/DronePath).
