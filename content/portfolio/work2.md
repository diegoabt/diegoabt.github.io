+++
date = "2016-11-05T19:41:01+05:30"
title = "Principled network extraction from images"
draft = false
image = "img/portfolio/river.png"
showonlyimage = false
weight = 2
+++

_**Diego Baptista** & Caterina De Bacco_

We present a principled model to extract network topologies from images that is scalable and efficient.


<!--more-->
![ALT](/img/portfolio/header_river.png){: .shadow}

### Abstract

Images of natural systems may represent patterns of network-like structure, which could reveal important information about the topological properties of the underlying subject. However, the image itself does not automatically provide a formal definition of a network in terms of sets of nodes and edges. Instead, this information should be suitably extracted from the raw image data. Motivated by this, we present a principled model to extract network topologies from images that is scalable and efficient. We map this goal into solving a routing optimization problem where the solution is a network that minimizes an energy function which can be interpreted in terms of an operational and infrastructural cost. Our method relies on recent results from optimal transport theory and is a principled alternative to standard image-processing techniques that are based on heuristics. We test our model on real images of the retinal vascular system, slime mould and river networks and compare with routines combining image-processing techniques. Results are tested in terms of a similarity measure related to the amount of information preserved in the extraction. We find that our model finds networks from retina vascular network images that are more similar to hand-labelled ones, while also giving high performance in extracting networks from images of rivers and slime mould for which there is no ground truth available. While there is no unique method that fits all the images the best, our approach performs consistently across datasets, its algorithmic implementation is efficient and can be fully automatized to be run on several datasets with little supervision.

> [Pdf: Principled network extraction from images](https://royalsocietypublishing.org/doi/epdf/10.1098/rsos.210025)

> [Preprint: Principled network extraction from images](https://arxiv.org/abs/2012.12758)

> [Code: Img2net](https://github.com/diegoabt/Img2net)
 

![ALT](/img/portfolio/river.png)