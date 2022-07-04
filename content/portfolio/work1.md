+++
showonlyimage = false
draft = false
image = "img/portfolio/fungi.png"
date = "2016-11-05T18:25:22+05:30"
title = "Network extraction by routing optimization"
weight = 1
+++

_**Diego Baptista**, Daniela Leite, Enrico Facca, Mario Putti & Caterina De Bacco_

We introduce a method to extract network topologies from dynamical equations related to routing optimization under various parameters’ settings.


<!--more-->
![ALT](/img/portfolio/header.png){: .shadow}

### Abstract

Routing optimization is a relevant problem in many contexts. Solving directly this type of optimization problem is often computationally intractable. Recent studies suggest that one can instead turn this problem into one of solving a dynamical system of equations, which can instead be solved efficiently using numerical methods. This results in enabling the acquisition of optimal network topologies from a variety of routing problems. However, the actual extraction of the solution in terms of a final network topology relies on numerical details which can prevent an accurate investigation of their topological properties. In fact, in this context, theoretical results are fully accessible only to an expert audience and ready-to-use implementations for non-experts are rarely available or insufficiently documented. In particular, in this framework, final graph acquisition is a challenging problem in-and-of-itself. Here we introduce a method to extract network topologies from dynamical equations related to routing optimization under various parameters’ settings. Our method is made of three steps: first, it extracts an optimal trajectory by solving a dynamical system, then it pre-extracts a network, and finally, it filters out potential redundancies. Remarkably, we propose a principled model to address the filtering in the last step, and give a quantitative interpretation in terms of a transport-related cost function. This principled filtering can be applied to more general problems such as network extraction from images, thus going beyond the scenarios envisioned in the first step. Overall, this novel algorithm allows practitioners to easily extract optimal network topologies by combining basic tools from numerical methods, optimization and network theory. Thus, we provide an alternative to manual graph extraction which allows a grounded extraction from a large variety of optimal topologies. The analysis of these may open up the possibility to gain new insights into the structure and function of optimal networks. We provide an open source implementation of the code online.

> [Pdf: Network extraction by routing optimization](https://www.nature.com/articles/s41598-020-77064-4.pdf)

> [Preprint: Network extraction by routing optimization](https://arxiv.org/abs/2005.02805)

> [Code: Nextrout](https://github.com/Danielaleite/Nextrout)
 

![ALT](/img/portfolio/fungi.png)