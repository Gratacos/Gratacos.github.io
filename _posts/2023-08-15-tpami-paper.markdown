---
layout: post
title:  "Our Paper has been accepted to TPAMI!"
date:   2023-08-15 21:10:10 -0500
categories: jekyll update
---

Our paper, *Tree Recovery by Dynamic Programming*, has been accepted in IEEE Transactions on Pattern Analysis and Machine Intelligence! From working on the method itself, to the compiling results and making figures, this process has been difficult, but very rewarding. 

![Foto](/assets/tree-recovery.png){: width="500" }

The paper is about recovering trees from cyclic graphs that represent objects in nature. More specificly: there are many tree-like objects in nature: retinal blood vessels, plant roots, lung airways, etc. It is often desirable to analyze the structure of these objects from images, volumes, or point-clouds by obtaining a *skeleton* from these images. Unfortunately, these skeletons often contain unwanted cycles due to various issues throughout the imaging and skeletonization process. 

Our paper proposes a dynamic programming algorithm for solving the NP-hard tree-recovery problem for retrieving an acyclic skeleton from these cyclic graphs by partitioning nodes. 

The paper can be found [here](https://ieeexplore.ieee.org/document/10197214).