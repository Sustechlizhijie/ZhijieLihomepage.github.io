---
title: "Long-term predictions of turbulence by implicit U-Net enhanced Fourier neural operator"
collection: publications
permalink: /publications/IUFNO
excerpt: ''
date: 2023-07-01
venue: 'Physics of Fluids'
paperurl: 'https://github.com/Sustechlizhijie/ZhijieLihomepage.github.io/blob/master/files/IUFNO.pdf'
citation: 'Zhijie Li, Wenhui Peng, Zelong Yuan and Jianchun Wang, "Long-term predictions of turbulence by implicit U-Net enhanced Fourier neural operator." Physics of Fluids 35.7 (2023).'
---
Long-term predictions of nonlinear dynamics of three-dimensional (3D) turbulence are very challenging for machine learning approaches. In this paper, we propose an implicit U-Net enhanced Fourier neural operator (IU-FNO) for stable and efficient predictions on the long-term large-scale dynamics of turbulence. The IU-FNO model employs implicit recurrent Fourier layers for deeper network extension and incorporates the U-net network for the accurate prediction on small-scale flow structures. The model is systematically tested in large-eddy simulations of three types of 3D turbulence, including forced homogeneous isotropic turbulence, temporally evolving turbulent mixing layer, and decaying homogeneous isotropic turbulence. The numerical simulations demonstrate that the IU-FNO model is more accurate than other FNO-based models, including vanilla FNO, implicit FNO (IFNO), and U-Net enhanced FNO (U-FNO), and dynamic Smagorinsky model (DSM) in predicting a variety of statistics, including the velocity spectrum, probability density functions of vorticity and velocity increments, and instantaneous spatial structures of flow field. Moreover, IU-FNO improves long-term stable predictions, which has not been achieved by the previous versions of FNO. Moreover, the proposed model is much faster than traditional large-eddy simulation with the DSM model and can be well generalized to the situations of higher Taylor–Reynolds numbers and unseen flow regime of decaying turbulence.
