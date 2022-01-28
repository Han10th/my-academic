---
title: "Topology-Preserving Segmentation Network: A Deep Learning Segmentation
  Framework with Topology Constraint"
publication_types:
  - "0"
authors:
  - "*Admin*"
  - Lok Ming LUI
abstract: Segmentation is the corner brick for computer-assisted medical image
  analysis. The conventional way is to do pixel-wise classification on images to
  generate masks. However, for single connected components like kidneys or
  liver, a natural idea is to deform a ball to enclose the objective regions in
  the imaging to produce a simple-connected genus-0 mask shape, which is free of
  interruptions and inner holes. Inspired by this, in this paper, we propose our
  topology-preserving segmentation network for single-connected components (TPSN
  in short). Input a pair of the medical image and template mask, we use the
  UNet architecture to produce a diffeomorphism mapping that can transform the
  template mask into the predicted mask. The topology of the template mask shape
  will be preserved in the predicted transformed mask by the diffeomorphism
  mapping. Thus, it will result in a simply-connected genus-0 mask that fits the
  prior knowledge that the target is known to be single-connected. Besides, we
  also come up with a multi-scale TPSN that refine the masks from coarse to
  fine. To evaluate our method, we perform experiments on Ham10000 for 2D TPSN
  and KiTS21 for 3D TPSN. The results indicate our method can achieve better
  performance by dice score as well as IoU score compared to the baseline UNet
  segmentation with/without connected-component analysis (CCA). Besides, we also
  present a special case where our method can still produce reliable results,
  but pixel-wise segmentation by UNet and CCA can not process properly.
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
summary: in this paper, we propose our topology-preserving segmentation network
  for single-connected components (TPSN in short). Input a pair of the medical
  image and template mask, we use the UNet architecture to produce a
  diffeomorphism mapping that can transform the template mask into the predicted
  mask. The topology of the template mask shape will be preserved in the
  predicted transformed mask by the diffeomorphism mapping. Thus, it will result
  in a simply-connected genus-0 mask that fits the prior knowledge that the
  target is known to be single-connected.
date: 2022-01-24T16:03:07.286Z
---
