---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Current work
permalink: /current_work/

---

# Current work

I am currently working at the Auckland Bioengineering Institute ([ABI](https://www.auckland.ac.nz/en/abi.html))
as part of their Software team. My job is to create 3D models of anatomical structures (AKA 'scaffolds')
to be used by other teams around the institute (and sometimes even ourselves) in a variety of 
healthcare-related projects, like the Stimulating Peripheral Activity to Relieve Conditions ([SPARC](https://sparc.science/)), 
Virtual Twins as tools for personalised clinicAL care ([VITAL](https://vital-horizoneurope.eu/)) 
and Topological Atlas and Repository for Acupoint Research ([TARA](https://tara-repository.mgb.org/))

The aim of the SPARC project is to map the very complicated system of nerves and organs in the human 
body (although we do have models for some animals as well). One of the key tools to achieve this 
objective is the 3D whole body model, which is the result of many years of cross-referencing
between anatomical data and computational tools. 
You can learn more about it [here]({{ "/publications/abi_paper_wbs/" | relative_url }})

{% include figures.html 
   src="/assets/abi_wbs.jpeg" 
   alt="3D human whole-body model" %}

This model includes all mayor nerves, organs, muscles, and blood vessels of the body. It is 
under constant development, with new features added as they are needed. For example, you might
notice that the model does not have much in the way of a hand these days (its more of a flipper, really). 
My latest task as part of the software team is to develop a new hand scaffold, that both is lightweight 
enough that we can 'stitch' it with the rest of the body without it becoming unwieldy. However, 
it also has to be detailed enough to be useful (e.g. be able to locate individual vessels or 
acupuncture points on it). 

The scaffolds are made using the [CMLibs Zinc](https://cmlibs.org/) Library and the 
Musculoskeletal Atlas Project ([MAP](https://sparc.science/tools-and-resources/1mv8q3JckdpSYpPK9dvdKx)) 
mapping tools, a series of Python libraries that allow us to create these complex 3D structures
using a high-level scripting language and (more than) a little maths. With these tools it is possible
to create a 3D finite element mesh created by extensive study of the anatomy of the hand and the
bones that comprise it. 

{% include figures.html 
   src="/assets/hand_scaffold.png" 
   alt="3D human whole-body model" %}

Of course this mesh is an _idealized_ version of a hand, with the real thing being much more 
complicadted. But one of the advantages of creating a finite element representation of this object
is that we can **fit** this mesh to whatever experimental data we managed to get our _hands_ on. Like, for example,
a 3D reconstruction of a hand made by a small scale scanner. 

{% include figures.html 
   src="/assets/hand_fitted.png" 
   alt="3D human whole-body model" %}

