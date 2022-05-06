---
layout: page
permalink: /TopoVoronoi/
title: "Cellular Topology Optimization on Differentiable Voronoi Diagrams"
---
## Cellular Topology Optimization on Differentiable Voronoi Diagrams
Submitted to Computer Methods in Applied Mechanics and Engineering (CMAME)<br>

<a href="https://sking8.github.io/"><b>Fan Feng</b></a>, <a href="https://shiyingxiong.github.io/">Shiying Xiong</a>, <a href="https://www.ziyueliu.space/">Ziyue Liu</a>, Zangyueyang Xian, <a href="http://www-personal.umich.edu/~yuqingz/">Yuqing Zhou</a>, Hiroki Kobayashi, Atsushi Kawamoto, Tsuyoshi Nomura, <a href="https://cs.dartmouth.edu/~bozhu/">Bo Zhu</a><br>
<b>[<a href="https://arxiv.org/pdf/2204.10313.pdf">paper</a>][<a href="https://youtu.be/pXEM0PZKp48">video</a>]</b>

<img src="../../../assets/img/paper/topo_voronoi.png" alt="topo_voronoi">

## Abstract

Cellular structures manifest their outstanding mechanical properties in many biological systems. One key challenge for designing and optimizing these geometrically complicated structures lies in devising an effective geometric representation to characterize the system's spatially varying cellular evolution driven by objective sensitivities. A conventional discrete cellular structure, e.g., a Voronoi diagram, whose representation relies on discrete Voronoi cells and faces, lacks its differentiability to facilitate large-scale, gradient-based topology optimizations. We propose a topology optimization algorithm based on a differentiable and generalized Voronoi representation that can evolve the cellular structure as a continuous field. The central piece of our method is a hybrid particle-grid representation to encode the previously discrete Voronoi diagram into a continuous density field defined in a Euclidean space. Based on this differentiable representation, we further extend it to tackle anisotropic cells, free boundaries, and functionally-graded cellular structures. Our differentiable Voronoi diagram enables the integration of an effective cellular representation into the state-of-the-art topology optimization pipelines, which defines a novel design space for cellular structures to explore design options effectively that were impractical for previous approaches. We showcase the efficacy of our approach by optimizing cellular structures with up to thousands of anisotropic cells, including femur bone and Odonata wing.

## Video / Results

<div class="videoWrapper">
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/pXEM0PZKp48" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>