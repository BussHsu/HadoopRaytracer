HadoopRayTracer
===============
 
 
## Introduction
This is a class project for COEN 283 Operating System in Fall 2017. This project is based on https://github.com/flexwang/HadoopRayTracer, with workload optimization for a two computer cluster with similar computing capacity. The basic idea for the optimization is to divide one image into two sets of scanlines: odd and even, and assign each computing node for a set of scanlines. It's faster because the diffuse material(computational easy) and reflective/refractive material(computational heavy) are shared evenly to each nodes, thus prevent one node idly waiting for another node. 

Please refer to the original author's github and report for more info.


