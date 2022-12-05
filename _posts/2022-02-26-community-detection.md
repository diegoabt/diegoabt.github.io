---
layout: post
title: Community detection in networks by dynamical optimal transport formulation
subtitle: We use OT-based tools to find hidden communities on networks.
thumbnail-img: /assets/img/img_community.png
gh-repo: Danielaleite/ORC-Nextrout
gh-badge: [star, fork, follow]
tags: [paper]
comments: true
---

**Abstract:** Detecting communities in networks is important in various domains of applications. While a variety of methods exist to perform this task, recent efforts propose Optimal Transport (OT) principles combined with the geometric notion of Ollivier–Ricci curvature to classify nodes into groups by rigorously comparing the information encoded into nodes’ neighborhoods. We present an OT-based approach that exploits recent advances in OT theory to allow tuning between different transportation regimes. This allows for better control of the information shared between nodes’ neighborhoods. As a result, our model can flexibly capture different types of network structures and thus increase performance accuracy in recovering communities, compared to standard OT-based formulations. We test the performance of our algorithm on both synthetic and real networks, achieving a comparable or better performance than other OT-based methods in the former case, while finding communities that better represent node metadata in real data. This pushes further our understanding of geometric approaches in their ability to capture patterns in complex networks.