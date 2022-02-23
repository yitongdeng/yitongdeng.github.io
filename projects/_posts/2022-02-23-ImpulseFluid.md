---
layout: page
permalink: /ImpulseFluid/
title: "Impulse Fluid"
---
<style type="text/css" media="screen">
  .videoWrapper {
      position: relative;
      padding-bottom: 56.25%;
      /* 16:9 */
      padding-top: 25px;
      height: 0;
    }
    
  .videoWrapper iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
</style>


## Impulse Fluid Simulation
IEEE Transactions on Visualization and Computer Graphics (TVCG)<br>
<a href="https://sking8.github.io/"><b>Fan Feng</b><a>, <a href="https://jyl-pages.github.io/">Jinyuan Liu</a>, <a href="https://shiyingxiong.github.io/">Shiying Xiong</a>, <a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9707648">Shuqi Yang</a>, <a href="http://portfolio.yaorui.info/">Yaorui Zhang</a>, <a href="https://cs.dartmouth.edu/~bozhu/">Bo Zhu</a><br>
<b>[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9707648">paper</a>][<a href="https://youtu.be/MFAXIETFC9M">video</a>]</b>

<img src="../../../assets/img/paper/impulse.jpg" alt="impulse_fluid">

## Abstract

We propose a new incompressible Navier–Stokes solver based on the impulse gauge transformation. The mathematical
model of our approach draws from the impulse–velocity formulation of Navier–Stokes equations, which evolves the fluid impulse as an
auxiliary variable of the system that can be projected to obtain the incompressible flow velocities at the end of each time step. We solve
the impulse-form equations numerically on a Cartesian grid. At the heart of our simulation algorithm is a novel model to treat the
impulse stretching and a harmonic boundary treatment to incorporate the surface tension effects accurately. We also build an impulse
PIC/FLIP solver to support free-surface fluid simulation. Our impulse solver can naturally produce rich vortical flow details without
artificial enhancements. We showcase this feature by using our solver to facilitate a wide range of fluid simulation tasks including
smoke, liquid, and surface-tension flow. In addition, we discuss a convenient mechanism in our framework to control the scale and
strength of the turbulent effects of fluid.

## Video / Results

<div class="videoWrapper">
<iframe width="100%" height="100%" src="https://www.youtube.com/embed/MFAXIETFC9M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

<br>
## Citation
```
@ARTICLE{9707648,
  author={Feng, Fan and Liu, Jinyuan and Xiong, Shiying and Yang, Shuqi and Zhang, Yaorui and Zhu, Bo},
  journal={IEEE Transactions on Visualization and Computer Graphics}, 
  title={Impulse Fluid Simulation}, 
  year={2022},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TVCG.2022.3149466}}
```