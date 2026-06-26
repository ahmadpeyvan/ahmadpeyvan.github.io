---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<a href="{{ base_path }}/files/CV_Ahmad_Peyvan.pdf" class="btn btn--primary">Download CV (PDF)</a>

Education
======
* Ph.D. in Mechanical Engineering, University of Illinois at Chicago, 2022 (GPA: 4.0/4.0)
* M.S. in Mechanical Engineering — Energy Conversion, Sharif University of Technology, 2013 (GPA: 3.69/4.0)
* B.S. in Mechanical Engineering — Heat and Fluids, Shiraz University, 2011 (GPA: 3.65/4.0)

Work experience
======
* Aug 2024 – Dec 2025: Assistant Professor of Applied Mathematics (Research), Brown University, Providence, RI
  * LLM-driven multi-agent virtual laboratory framework for aerial vehicle geometric design.
  * Advised a PhD student on reduced-order dynamical models for supersonic/hypersonic intakes using PINNs.
  * Advised an undergraduate student on robust inverse design of electromagnetic devices using uncertainty-quantified neural operators and CVaR optimization.
  * Geometry-dependent neural operators for hypersonic flow prediction on arbitrary grids with limited data.
  * High-order spectral element solver for hypersonic flows with high parallel efficiency, adaptive mesh refinement, and realistic thermophysical modeling.

* Dec 2023 – Aug 2025: Artificial Intelligence Specialist, PredictiveIQ, Providence, RI
  * Shape optimization of industrial evaporators to maximize heat transfer.
  * Deep Operator Network surrogates for boiling-refrigerant heat transfer inside evaporator coils.
  * Deep-learning surrogate for incompressible flow around Scania trucks to optimize cabin shape and reduce drag.
  * General geometry parameterization of 3D point clouds using deep neural networks (PointNet).

* Jan 2022 – Jul 2024: Postdoctoral Research Associate, Brown University, Providence, RI
  * Entropy-stable discontinuous Galerkin spectral element method in Julia for inviscid hypersonic flows.
  * Deep neural operator surrogates to infer airfoil flow fields and perform geometric optimization.
  * DNS of laminar-to-turbulent transition in hypersonic boundary layers (Fortran).
  * Deep neural operators for learning solutions of Riemann problems (JAX).

* Jan 2017 – Dec 2022: Research Assistant, University of Illinois at Chicago, Chicago, IL
  * 3D compressible flow solver (discontinuous spectral element method) in MPI-Fortran, scaling to 130,000 processors.
  * Developed the flux reconstruction discontinuous spectral element method (FRDSEM) for the compressible Navier–Stokes equations.
  * Double-flux and shock-capturing techniques for multicomponent compressible turbulent flows in shock tubes.
  * Simulation of COVID-19 propagation in a dental clinic (ANSYS/Fluent).

* Jan 2017 – Dec 2022: Intern, Industrial Assessment Center, Chicago, IL
  * Energy-efficiency assessments for small-to-medium plants under a U.S. Department of Energy grant; identified >$130,000 in potential annual savings.

* Sep 2011 – Sep 2013: Research Assistant, Sharif University of Technology, Tehran, Iran
  * MATLAB code for axial-flow compressor design; performance studies via ANSYS/CFX; turbojet engine testing.

Grants
======
* **PI** — NSF ACCESS supercomputing allocation: "Large Eddy Simulations of Chemically Reacting Turbulent Flow."
* **Co-PI** — NCSA supercomputing allocation: "DNS Investigation of Compressibility Effects on Separating and Reattaching Shear Layers."
* **Writing** — DURIP GPU Cluster for Neural PDEs and Neural Operators (MURI support): \$750,000 (02/2024–01/2025).
* **Writing** — MURI Add-on: Physics-Informed Neural Networks for High-Speed Flows (AFOSR): \$300,000.
* **Writing** — SMASH project: Heat Transfer on Hypersonic Vehicles (ARL): \$200,000.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks and conference presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
* Introduction to Thermodynamics (TA), University of Illinois at Chicago
* Air Pollution Control (TA, graduate), University of Illinois at Chicago
* Gas Turbine (TA), Sharif University of Technology

Honors and awards
======
* Featured article, *Physics of Fluids* — "Computer simulation of the SARS-CoV-2 contamination risk in a large dental clinic."
* Top-ten download list (SSRN, Chemical Physics eJournal) — "High-order methods for hypersonic flows with strong shocks and real chemistry."
* College of Engineering Fellowship, University of Illinois at Chicago, 2017.
* Industrial Assessment Center (IAC) certificate for exceptional participation (U.S. DOE).
* Ranked 1st GPA, B.Sc. class of 2007, School of Mechanical Engineering, Shiraz University.
* Ranked 6th of 60+ in the Mechanical Engineering Students Olympiad, Iran, 2011.
* Ranked 10th of 1,700+ in the Ph.D. program university entrance exam, Iran, 2014.

Skills
======
* **Programming:** Fortran, MATLAB, Julia, C++, Python, Maple, Shell scripting
* **Parallel programming:** MPI, OpenMP
* **Machine learning:** JAX, PyTorch, TensorFlow
* **CFD software:** ANSYS/Fluent, ANSYS/CFX, OpenFOAM
* **Mesh generation:** GridPro, ANSYS Meshing, Trelis, Gambit
* **Post-processing:** ParaView, VisIt, Tecplot, matplotlib, MATLAB
* **CAD:** SolidWorks

Service and affiliations
======
* **Journal reviewer:** Journal of Computational Physics; Physics of Fluids; Computer Methods in Applied Mechanics and Engineering; Journal of Fluid Mechanics
* **Member:** American Institute of Aeronautics and Astronautics (AIAA); American Physical Society, Division of Fluid Dynamics (APS-DFD)
