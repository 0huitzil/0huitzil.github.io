---
layout: default
title: "A Model for the Coexistence of Competing Mechanisms for Oscillations in T-lymphocytes"
permalink: /publications/phd_paper_2/
---

## A Model for the Coexistence of Competing Mechanisms for Oscillations in T-lymphocytes


{% include figures.html 
   src="/assets/phd_paper2_full.png" 
   alt="Model of calcium oscillations" %}

{% include buttons.html 
   article_url="https://doi.org/10.1007/s11538-024-01317-w"
   code_url="https://github.com/0huitzil/jurkatModel" %}

### Summary:

This is the first out of three papers that came out of a collaboration between my supervisor James Sneyd and the [Trebak Lab](https://trebaklab.com/) at the University of Pittsburgh. The team at the Trebak Lab were _calcium signalling_ in T-cells; in other words, they were studying the transport of Ca<sup>2+</sup> in and out of these cells. It was pretty well known at the time of publication that Ca<sup>2+</sup> signals in these cells were driven by a Ca<sup>2+</sup> release-activated Ca<sup>2+</sup> (**CRAC**) channel, which sits on the membrane of the cell. So a natural question for them to ask was: what happens when that channel stops working? 

To do that, they disabled the two molecular 'switches' that make up the CRAC channel: the **STIM1** and **STIM2** proteins. In the image above, you can see the type of oscillations seen in a 'healthy' cell in black (WT), and those observed in a cell without STIM1 in red (STIM1 KO) and without STIM2 in blue (STIM2 KO). What the team were expecting to see was oscillations disappearing in cells without STIM1 and/or STIM2, What they found instead is that a second type of oscillations rises in these scenarios. 

My supervisor and I were then approached to create a model which could reproduce these results (and hopefully shine some light on _why_ this was happening). A preliminary version of our mathematical model is included in the later section of this paper, and the experimental data will be the basis of the two others papers I published on my PhD work. 
