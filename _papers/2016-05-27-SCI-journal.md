---
title: "Domain Decomposition Parallel Computing for Transient Two-phase Flow of Nuclear Reactors"
categories:
  - SCI
tags:

---

[Journal of Mechanical Science and Technology, VOl.30, No.5, pp.2045-2057, 2016](https://doi.org/10.1007/s12206-016-0411-3)


## Author

J.R.Lee, H.Y.Yoon, H.G.Choi

----

>KAERI (Korea Atomic Energy Research Institute) has been developing a multi-dimensional two-phase flow code named CUPID for multi-physics and multi-scale thermal hydraulics analysis of Light water reactors (LWRs). The CUPID code has been validated against a set of conceptual problems and experimental data. In this work, the CUPID code has been parallelized based on the domain decomposition method with Message passing interface (MPI) library. For domain decomposition, the CUPID code provides both manual and automatic methods with METIS library. For the effective memory management, the Compressed sparse row (CSR) format is adopted, which is one of the methods to represent the sparse asymmetric matrix. CSR format saves only non-zero value and its position (row and column). By performing the verification for the fundamental problem set, the parallelization of the CUPID has been successfully confirmed. Since the scalability of a parallel simulation is generally known to be better for fine mesh system, three different scales of mesh system are considered: 40000 meshes for coarse mesh system, 320000 meshes for mid-size mesh system, and 2560000 meshes for fine mesh system. In the given geometry, both single- and two-phase calculations were conducted. In addition, two types of preconditioners for a matrix solver were compared: Diagonal and incomplete LU preconditioner. In terms of enhancement of the parallel performance, the OpenMP & MPI hybrid parallel computing for a pressure solver was examined. It is revealed that the scalability of hybrid calculation was enhanced for the multi-core parallel computation.

[https://doi.org/10.1007/s12206-016-0411-3](https://doi.org/10.1007/s12206-016-0411-3)