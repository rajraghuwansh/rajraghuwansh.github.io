---
title: 🧭 Spherical Harmonics and the Spherical Coordinate System
summary: Understanding spherical coordinates and spherical harmonics — the mathematical foundation behind many applications in physics, geometry, and machine learning.
date: 2026-03-16
authors:
  - me
tags:
  - Mathematics
  - Spherical Harmonics
  - Geometric Deep Learning
  - Coordinate Systems
  - Harmonic Analysis
math: true
cover:
  image: "https://images.unsplash.com/photo-1635070041078-e363dbe005cb?q=80&w=2560"
  position:
    x: 50
    y: 40
  overlay:
    enabled: true
    type: "gradient"
    opacity: 0.4
    gradient: "bottom"
  fade:
    enabled: true
    height: "80px"
  icon:
    name: "🌍"
image:
  caption: "Spherical geometry plays a fundamental role in physics, signal processing, and geometric deep learning."
---

Spherical harmonics are one of the most important mathematical tools for analyzing functions defined on the surface of a sphere. They appear in many areas including **quantum mechanics, geophysics, computer graphics, and modern geometric deep learning**.

This post introduces the **spherical coordinate system** and explains how spherical harmonics arise naturally when studying functions on the sphere.

<!--more-->

## The Spherical Coordinate System

In three-dimensional space, we often represent points using **Cartesian coordinates**

\[
(x, y, z)
\]

However, when working with spherical objects or rotationally symmetric problems, it is more natural to use **spherical coordinates**:

\[
(r, \theta, \phi)
\]

where:

- \(r\) is the distance from the origin  
- \(\theta\) is the polar angle (measured from the z-axis)  
- \(\phi\) is the azimuthal angle (measured in the xy-plane)

The relationship between Cartesian and spherical coordinates is:

\[
x = r \sin\theta \cos\phi
\]

\[
y = r \sin\theta \sin\phi
\]

\[
z = r \cos\theta
\]

This coordinate system is particularly useful when studying functions defined on the **surface of a sphere**, where \(r\) is constant.

---

## What Are Spherical Harmonics?

Spherical harmonics are a set of special functions defined on the sphere that form an **orthogonal basis** for functions on the sphere.

They are analogous to **Fourier series**, but instead of decomposing functions on a circle, they decompose functions on a **sphere**.

A spherical harmonic is usually written as

\[
Y_l^m(\theta, \phi)
\]

where:

- \(l\) is the degree
- \(m\) is the order
- \(-l \le m \le l\)

These functions arise as solutions to **Laplace's equation in spherical coordinates**.

---

## Why Spherical Harmonics Matter

Spherical harmonics appear in many scientific fields:

### Physics
They are used to solve:

- Schrödinger equation
- gravitational potentials
- electromagnetic fields

### Computer Graphics
They are used for:

- lighting models
- environment maps
- rendering reflections

### Geometric Deep Learning

Modern AI models that operate on **spheres, rotations, or 3D structures** often rely on spherical harmonics for:

- equivariant neural networks
- molecular modeling
- 3D vision

---

## Visualizing the Harmonics

Each spherical harmonic corresponds to a particular **frequency pattern on the sphere**.

Low-degree harmonics represent **smooth variations**, while higher-degree harmonics represent **finer oscillations**.

Conceptually:
