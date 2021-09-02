---
abstract: ""
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Admin
  - Yucong Yao
  - Ke Xie
  - Chi-Wing Fu
  - Hao Zhang
  - Hui Huang
author_notes: []
publication: Siggraph Asia 2021
summary: >-
  We introduce the first path-oriented drone trajectory planning algorithm,
  which performs continuous (i.e., dense) image acquisition along an aerial path
  and explicitly factors path quality into an optimization along with scene
  reconstruction quality. Specifically, our method takes as input a rough 3D
  scene proxy and produces a drone trajectory and image capturing setup, which
  efficiently yields a high-quality reconstruction of the 3D scene based on
  three optimization objectives: one to maximize the amount of 3D scene
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
   reconstruction, compared to existing planning methods and oblique photography, a mature and popular industry solution.
url_dataset: ""
url_project: ""
publication_short: SIGA21
url_source: ""
url_video: ""
title: Continuous Aerial Path Planning for 3D Urban Scene Reconstruction
doi: ""
featured: true
tags: []
projects:
  - Reconstruction
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2021-09-02T10:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
