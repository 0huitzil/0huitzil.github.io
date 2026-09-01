---
layout: default
title: "Modelling the role of STIM1 and STIM2 in Ca2+ oscillations in T-lymphocytes"
permalink: /publications/phd_paper_3/
---

## Modelling the role of STIM1 and STIM2 in Ca<sup>2+</sup> oscillations in T-lymphocytes



{% include buttons.html 
   article_url="https://doi.org/10.1007/s11538-025-01559-2"
   code_url="https://github.com/0huitzil/jurkatSTIMKO" %}


After successfully coming up with a hypothesis regarding the two oscillatory mechanisms 
seen in T-cells in our [previous paper]({{ "/publications/phd_paper_2/" | relative_url }}), 
there remained a very annoyingly difficult to answer question: “What was the role of
STIM1 and STIM2 in this whole ordeal?” We knew that the **external oscillatory mechanism** (CRAC)
relied on these two proteins to function. We also knew that oscillations in cells with both types of STIM (purple) 
have a sinusoidal shape, and that those with neither type (now shown here) consisted of spikes and bursts.
To complicate things even more, cells without STIM2 (red) or STIM1 (blue) exhibited oscillations
that sometimes had spikes, and sometimes had a Ca<sup>2+</sup> 'swell'(not a full sinusoidal wave, but almost). 

{% include figures.html 
   src="/assets/phd_paper3_data.png" 
   alt="Calcium oscillations on T-cells" %}

It was becoming obvious that in this intermediate stages, both mechanisms could cooperate to 
create a 'mixed' or 'hybrid' type of oscillation. But we still needed to show computational 
evidence, at least, that this was the case. So back to the drawing board we went and what we came 
up with a simple model of interaction between STIM1 (blue) and STIM2 (red), as in the following diagram.
In short, this model proposed that STIM1 and STIM2 can both enable Ca<sup>2+</sup> influx, but when they
are together they can cooperate to create a transport mechanism stronger than the sum of its parts (purple).
{% include figures.html 
   src="/assets/phd_paper3.png" 
   alt="Model of STIM binding" %}


This model not only allowed us to performed simulations of cells under these three scenarios:
-  with both STIMs are present (purple),
which have the characteristic sinusoidal shape
- without STIM1 (red), comprised of
both 'spikes' and 'swells' but that only oscillated in a small range of values
- without STIM2 (blue) similar to the previous case, but with more prominent 'swells'

{% include figures.html 
   src="/assets/phd_paper3_simulations.png" 
   alt="Computational simulation of a model of calcium oscillations" %}

Which was pretty exciting! Problem solved, right? Well, we still needed to show that the
hybrid oscillations were possible from a mathematical point of view (which would give us a 
better understanding of how the two mechanisms work together), but time became my greatest enemy 
and I had to finish my PhD studies before tackling that question. Perhaps one day… 