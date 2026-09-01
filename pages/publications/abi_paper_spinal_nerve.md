---
layout: default
title: "Generic human spinal nerves scaffold"
permalink: /publications/abi_paper_spinal_nerve/
---


## Generic human spinal nerves scaffold


{% include buttons.html 
   article_url="https://doi.org/10.26275/s0po-usdk"
   dataset_url="https://sparc.science/datasets/445?datasetDetailsTab=files"
   code_url = "https://github.com/ABI-Software/scaffoldmaker" %}

The human spinal nerves scaffold is meant to represent the 31 pairs of spinal nerves that populate 
the vertebral column. It is created by positioning 62 copies of a 
singular [spinal nerve]({{ "/publications/abi_paper_drg/" | relative_url }}) scaffold 
alongside a path which mimics the actual curvature of the spine in humans
(As an aside, trying to get a good angle of this scaffold for the publication was much 
harder than it looks).

The primary use of this scaffold is to be embedded into our 
[3D whole body]({{ "/publications/abi_paper_wbs/" | relative_url }}), as 
part of the [SPARC](https://sparc.science/) project. 
The scaffold is parametrised according to anatomical data, ready to be fit to experimental datasets! 

{% include figures.html 
   src="/assets/abi_spinal_nerve.jpeg" 
   alt="Generic human spinal nerves scaffold" %}