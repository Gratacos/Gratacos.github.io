# Tree Recovery by Dynamic Programming

![Foto](/assets/tree-recovery.png){: width="500" }

There are many tree-like objects in nature: retinal blood vessels, plant roots, lung airways, etc. It is often desirable to analyze the structure of these objects from images, volumes, or point-clouds by obtaining a *skeleton* from these images. Unfortunately, these skeletons often contain unwanted cycles due to various issues throughout the imaging and skeletonization process. 

We propose a dynamic programming algorithm for solving the NP-hard tree-recovery problem for retrieving an acyclic skeleton from these cyclic graphs. This work is published in [IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/document/10197214). 

# Plant Segmentation with Graph Cuts 

![Foto](/assets/plant-segmentation.gif){: width="500" }

For this work, we made a UI to segment a series of overhead images of plant, with the constraint that each segmentation must be consistent with the next. This tool also allows you to select a region of interest, and to manually “clean up” the resulting segmentation. 

We presented this work in the 2021 _Annual North American Plant Phenotyping Network Conference_ in the poster: “Temporally Consistent Multi-label Plant-level Segmentation of Overhead Images for High-throughput Phenotyping.” Furthermore, this UI was created as part of the work published in: [The plant response to high CO2 levels is heritable and orchestrated by DNA methylation](https://nph.onlinelibrary.wiley.com/doi/full/10.1111/nph.18876). 
