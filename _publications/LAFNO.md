---
title: "Linear attention coupled Fourier neural operator for simulation of three-dimensional turbulence"
collection: publications
permalink: /publications/LAFNO
excerpt: ''
date: 2023-01-01
venue: 'Physics of Fluids'
paperurl: 'https://github.com/Sustechlizhijie/ZhijieLihomepage.github.io/files/LAFNO.pdf'
citation: 'Wenhui Peng, Zelong Yuan, Zhijie Li and Jianchun Wang, "Linear attention coupled Fourier neural operator for simulation of three-dimensional turbulence." Physics of Fluids 35.1 (2023).'
---
Modeling three-dimensional (3D) turbulence by neural networks is difficult because 3D turbulence is highly nonlinear with high degrees of freedom and the corresponding simulation is memory-intensive. Recently, the attention mechanism has been shown as a promising approach to boost the performance of neural networks on turbulence simulation. However, the standard self-attention mechanism uses  $O(n^2)$ time and space with respect to input dimension n , and such quadratic complexity has become the main bottleneck for attention to be applied on 3D turbulence simulation. In this work, we resolve this issue with the concept of a linear attention network. The linear attention approximates the standard attention by adding two linear projections, reducing the overall self-attention complexity from $O(n^2)$ to  $O(n)$ in both time and space. The linear attention coupled Fourier neural operator (LAFNO) is developed for the simulation of 3D isotropic turbulence and free shear turbulence. Numerical simulations show that the linear attention mechanism provides 40% error reduction at the same level of computational cost, and LAFNO can accurately reconstruct a variety of statistics and instantaneous spatial structures of 3D turbulence. The linear attention method would be helpful for the improvement of neural network models of 3D nonlinear problems involving high-dimensional data in other scientific domains.
