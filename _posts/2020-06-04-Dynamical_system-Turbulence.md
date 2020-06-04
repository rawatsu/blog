---
layout: post
title: Dynamical system understanding of Turbulence
categories: Turbulence Fluid-Dynamics Dynamical-system
usemathjax: true
---

In last few decades, dynamical system theory have found its way to theory of turbulence. Fluid flow can be explained from the solution of Navier-Stokes equation. The solution described by this  nonlinear partial differential equation is infinite dimensional, as one need infinite ordinary differential equation to solve this PDE. [Hopf](https://en.wikipedia.org/wiki/Eberhard_Hopf) conjectured that solution of N-S equations can be represented as a point in an infinite-dimensional phase space of the problem, constituted by suitably chosen state space variables. 

>He further hypothesized that these solution lie on a finite dimensional manifold, size of whose dimension depends upon the viscosity, varing from 0 for $$\nu \to \infty$$, to $$\infty$$ for $$\nu \to 0$$. This low-dimensional manifold  becomes unstable and bifurcates into many other branches as viscosity $$\nu$$ is decreased. 

It can be demonstrated mathematically that the solutions of dissipative PDE's are restricted to global attracters which are embedded in inertial manifolds.

In dynamic system theory the equation of motion is  generally represented as :

 $$\frac{d{**u**}}{dt} = **f**(**u**,\nu)$$
where **f** is a evolution function that map one point in phase space to another. For a deterministic dynamical system like Navier-Stokes, each single point in phase space represents a physical state of the system. Coherent structures observed in turbulent flows are considered 
to be as low-dimensional invariant sets in phase space. These invariant states can be classified into three main categories :
                              
     *$$\frac{d\textbf{u}}{dt} = f(u,\nu) = 0$$; Travelling waves, equillibrium points.
     *$$\textbf{u(x,t)} = \textbf{u(x,t+T)}$$;  periodic or relative periodic orbits.
     *$$\textbf{u(x,t)} \neq \textbf{u(x,t')}$$;  for all \(t \neq t'\) aperiodic trajectories.
