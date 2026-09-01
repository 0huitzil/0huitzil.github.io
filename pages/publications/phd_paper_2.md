---
layout: default
title: "A Model for the Coexistence of Competing Mechanisms for Ca2+ Oscillations in T-lymphocytes"
permalink: /publications/phd_paper_2/
---

## A Model for the Coexistence of Competing Mechanisms for Ca<sup>2+</sup> Oscillations in T-lymphocytes

{% include buttons.html 
   article_url="https://doi.org/10.1007/s11538-024-01317-w"
   code_url="https://github.com/0huitzil/jurkatModel" %}

Following up from our [first paper]({{ "/publications/phd_paper_1/" | relative_url }}) 
with the [Trebak Lab](https://trebaklab.com/), 
my supervisors and I went back to the drawing board
to try to create a robust model that could replicate the different types of 
oscillations we observed on the experimental data. 
First, we focused solely on the unaltered (**WT**) cells, 
and realised that cells with access to an external source of Ca<sup>2+</sup>
(green) always oscillated with a broad 'wave-like' pattern; on the other hand, 
oscillations in cells deprived of 
external Ca<sup>2+</sup> (red, salmon, and orange) consisted of spikes and peaks


{% include figures.html 
   src="/assets/phd_paper2_data.png" 
   alt="Calcium oscillations on T-cells" %}


After many long nights of thinking about this phenomenon, we had an idea: what if the cells 
actually contained **two oscillatory mechanisms**? The **external mechanism** 
(shown in green) which was well studied at the time, 
and an **internal mechanism** (red) which was overshadowed in 'normal' circumstances, 
but resurfaces once the external mechanism was silenced (e.g. due to lack of an external source)? 
With this in mind we set off to create a system of ODEs (represented by the following diagram)
which could, under the right conditions, replicate these experimental results. 

{% include figures.html 
   src="/assets/phd_paper2_full.png" 
   alt="Model of calcium oscillations" %}

With the model in place we now could run simulations, like the ones in the following image:

{% include figures.html 
   src="/assets/phd_paper2_simulations.png" 
   alt="Computational simulation of a model of calcium oscillations" %}

Which look qualitatively similar to the data! This result was a great starting point, 
but it only explained the cases where the primary mechanisms is either fully switched 
on or off. What happened in situations where this mechanism was only partially switched off, 
like in cells without either **STIM1** or **STIM2**? 
[We still needed to figure that out…]({{ "/publications/phd_paper_3/" | relative_url }})
