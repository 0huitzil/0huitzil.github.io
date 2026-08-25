---
layout: default
title: "A multiple-oscillator mechanism underlies antigen-induced Ca<sup>2+</sup> oscillations in Jurkat T-cells"
permalink: /publications/phd_paper_1/
---

# A multiple-oscillator mechanism underlies antigen-induced Ca<sup>2+</sup> oscillations in Jurkat T-cells

![Calciumtraces]({{ "/assets/phd_paper1.jpg" | relative_url }})

{% include buttons.html 
   article_url="https://doi.org/10.1016/j.jbc.2023.105310" %}

### Summary:

This is the first out of three papers that came out of a collaboration between my supervisor James Sneyd and the [Trebak Lab](https://trebaklab.com/) at the University of Pittsburgh. The team at the Trebak Lab were _calcium signalling_ in T-cells; in other words, they were studying the transport of Ca<sup>2+</sup> in and out of these cells. It was pretty well known at the time of publication that Ca<sup>2+</sup> signals in these cells were driven by a Ca<sup>2+</sup> release-activated Ca<sup>2+</sup> (**CRAC**) channel, which sits on the membrane of the cell. So a natural question for them to ask was: what happens when that channel stops working? 

To do that, they disabled the two molecular 'switches' that make up the CRAC channel: the **STIM1** and **STIM2** proteins. In the image above, you can see the type of oscillations seen in a 'healthy' cell in black (WT), and those observed in a cell without STIM1 in red (STIM1 KO) and without STIM2 in blue (STIM2 KO). What the team were expecting to see was oscillations disappearing in cells without STIM1 and/or STIM2, What they found instead is that a second type of oscillations rises in these scenarios. 

My supervisor and I were then approached to create a model which could reproduce these results (and hopefully shine some light on _why_ this was happening). A preliminary version of our mathematical model is included in the later section of this paper, and the experimental data will be the basis of the two others papers I published on my PhD work. 

### Abstract:

T-cell receptor stimulation triggers cytosolic Ca<sup>2+</sup> signaling by inositol-1,4,5-trisphosphate (IP3)-mediated Ca<sup>2+</sup> release from the endoplasmic reticulum (ER) and Ca<sup>2+</sup> entry through Ca<sup>2+</sup> release-activated Ca<sup>2+</sup> (CRAC) channels gated by ER-located stromal-interacting molecules (STIM1/2). Physiologically, cytosolic Ca<sup>2+</sup> signaling manifests as regenerative Ca<sup>2+</sup> oscillations, which are critical for nuclear factor of activated T-cells-mediated transcription. In most cells, Ca<sup>2+</sup> oscillations are thought to originate from IP3 receptor-mediated Ca<sup>2+</sup> release, with CRAC channels indirectly sustaining them through ER refilling. Here, experimental and computational evidence support a multiple-oscillator mechanism in Jurkat T-cells whereby both IP3 receptor and CRAC channel activities oscillate and directly fuel antigen-evoked Ca<sup>2+</sup> oscillations, with the CRAC channel being the major contributor. KO of either STIM1 or STIM2 significantly reduces CRAC channel activity. As such, STIM1 and STIM2 synergize for optimal Ca<sup>2+</sup> oscillations and activation of nuclear factor of activated T-cells 1 and are essential for ER refilling. The loss of both STIM proteins abrogates CRAC channel activity, drastically reduces ER Ca<sup>2+</sup> content, severely hampers cell proliferation and enhances cell death. These results clarify the mechanism and the contribution of STIM proteins to Ca<sup>2+</sup> oscillations in T-cells.


