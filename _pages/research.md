---
title: "Research"
permalink: /research/
author_profile: true
---

My research develops high-order computational fluid dynamics methods and physics-aware
machine learning models for high-speed and reacting flows. Below are the main themes
of my work, with representative animations from recent projects.

<style>
.research-media {
  display: flex;
  flex-wrap: wrap;
  gap: 1em;
  margin: 1em 0 0.5em;
}
.research-media figure {
  margin: 0;
  flex: 1 1 360px;
  max-width: 520px;
}
.research-media video,
.research-media img {
  width: 100%;
  display: block;
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  background: #000;
}
.research-media figcaption {
  font-size: 0.85em;
  color: #666;
  padding: 0.4em 0.2em 0;
  line-height: 1.35;
}
.research-theme { margin-bottom: 2.5em; }
</style>

<!--
HOW TO ADD / SWAP MEDIA
=======================
Video: put an .mp4 in /files/ and reference it as /files/name.mp4
GIF/Image: put it in /files/ or /images/ and use the <img> variant.
Each theme is a <div class="research-theme"> with a heading, a paragraph,
and a <div class="research-media"> holding one or more <figure> blocks.
-->

<div class="research-theme" markdown="1">

## Hypersonic Flows & Turbulence

I develop high-order, shock-capturing methods (discontinuous Galerkin and spectral
element) for compressible and hypersonic flows — resolving strong shock–shock
interactions, real-gas chemistry, and the laminar-to-turbulent transition that
governs heating on high-speed vehicles.

<div class="research-media">
  <figure>
    <video autoplay loop muted playsinline poster="/images/doublecone-poster.jpg">
      <source src="/files/Doublecone.mp4" type="video/mp4">
    </video>
    <figcaption>Density field over a double cone, capturing shock–shock interaction and flow separation.</figcaption>
  </figure>
  <figure>
    <video autoplay loop muted playsinline>
      <source src="/files/rho_scramjet.mp4" type="video/mp4">
    </video>
    <figcaption>Turbulent high-speed density field in a scramjet configuration.</figcaption>
  </figure>
</div>

</div>

<div class="research-theme" markdown="1">

## Fast Geometry-Dependent Surrogates

I build neural operators that learn geometry-dependent flow fields, producing
accurate surrogate predictions across varying shapes orders of magnitude faster
than full CFD — enabling rapid design exploration and optimization.

<div class="research-media">
  <figure>
    <video autoplay loop muted playsinline>
      <source src="/files/no_del.mp4" type="video/mp4">
    </video>
    <figcaption>Surrogate prediction of a geometry-dependent flow field.</figcaption>
  </figure>
</div>

</div>

<div class="research-theme" markdown="1">

## Efficient Computations

I design adaptive, high-performance solvers — with error indicators, adaptive mesh
refinement, and massively parallel implementations — that concentrate resolution
where it matters and scale efficiently on large HPC systems.

<div class="research-media">
  <figure>
    <video autoplay loop muted playsinline>
      <source src="/files/indicator_airfoil.mp4" type="video/mp4">
    </video>
    <figcaption>Adaptive error indicator driving mesh refinement around an airfoil.</figcaption>
  </figure>
</div>

</div>

<div class="research-theme" markdown="1">

## Time-Dependent Neural Operators

I develop operator-learning architectures that capture the temporal evolution of
PDE solutions, enabling real-time inference and extrapolation for unsteady
high-speed flows.

<div class="research-media">
  <figure>
    <img src="/files/time_neural_operator.gif" alt="Time-dependent neural operator prediction vs. ground truth">
    <figcaption>Time-conditioned neural operator: predicted vs. ground-truth density evolution over a double cone.</figcaption>
  </figure>
</div>

</div>
