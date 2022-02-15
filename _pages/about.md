---
permalink: /about/
title: "About"
excerpt: "Introduction"
gallery:
  - url: /assets/images/cupid_logo1.png
    image_path: /assets/images/cupid_logo1.png
    alt: "CUPID_logo"
last_modified_at: 2022-01-19
toc: false
---

<!-- {% include gallery type="center" %} -->
![styled-image](/assets/images/cupid_logo1.png "CUPID_logo"){: .align-center style="width: 75%;"}

<!-- {% include figure image_path="/assets/images/cupid_logo3.png" alt="this is a placeholder image" class="align-center" style="width: 500px" %} -->


**CUPID** is a general-purpose high-resolution thermal hydraulics code for nuclear reactor safety. The 3-dimensional 2-fluid model and the unstructured mesh of CUPID make the software appropriate for a wide range of single- and 2-phase flow analysis of nuclear reactors with complicated geometries.

**CUPID** provides a unique and versatile interface with system thermal hydraulics, neutron kinetics, and fuel performance codes for the multi-scale and multi-physics (MSMP) coupled calculation, which is essential in nuclear reactor safety analysis.


## Features

- Finite Volume Method
- Unstructured Mesh: Tetrahedron, Polyhedron mesh
- Numerical Scheme: Semi-Implicit method, Fully-Implicit method
- Pressure Solver: Conjugate Gradient (CG) and Multi-Grid (MG) solvers
- Parallel: MPI, Hybrid-MPI (MPI-OpenMP)
- Two-phase Physical Models and Correlations
- Multi-scale Analysis: Implicit coupling with a system analysis code
- Multi-physics Analysis: Coupling with neutron kinetics and fuel performance codes

---

## Coupled Codes

### MARS:

   * System-scale Thermal-hydraulics Code
   * 1D Lumped parameter

### MASTER:

   * Neutron Kinetics Code
   * Multi-group Diffusion Equation

### FRAPTRAN:

   * Fuel Performance Code
   * 2D axis-symmetric


---


