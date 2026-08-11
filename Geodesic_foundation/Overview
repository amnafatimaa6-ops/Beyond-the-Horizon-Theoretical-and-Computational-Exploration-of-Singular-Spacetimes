# General Relativistic Geodesics Around a Schwarzschild Black Hole

## Overview

This notebook provides a computational introduction to how particles and light move through the curved spacetime surrounding a Schwarzschild black hole.

Instead of treating gravity as an ordinary force, the simulation uses the **geodesic equations of General Relativity** to calculate how objects follow curved paths through spacetime. The equations are solved numerically using the **fourth-order Runge–Kutta (RK4) method**.

The notebook starts from the Schwarzschild metric and gradually builds the numerical simulation, introducing the relevant Christoffel symbols, state vector, geodesic equations, initial conditions, and numerical integration.

## What This Notebook Does

The simulation:

* Defines the Schwarzschild spacetime using geometric units.
* Simplifies the motion to the equatorial plane.
* Introduces the relevant Christoffel symbols.
* Converts the second-order geodesic equations into a first-order system.
* Represents the particle's position and velocity using a six-component state vector.
* Implements a fourth-order Runge–Kutta (RK4) integrator from scratch.
* Sets initial position and velocity conditions for the particle.
* Numerically integrates the trajectory through curved spacetime.
* Converts the resulting polar coordinates into Cartesian coordinates.
* Visualises the particle's orbit around the black hole.
* Displays the Schwarzschild event horizon.
* Provides the foundation for studying more complicated photon and gravitational-lensing trajectories.

## Why RK4?

The geodesic equations are differential equations that generally cannot be solved easily in closed form for arbitrary initial conditions.

RK4 was chosen because it evaluates the derivative at **four points within every integration step** and combines those estimates to produce a more accurate trajectory than a basic first-order method such as Euler's method.

This is particularly useful for curved trajectories near a black hole, where small numerical errors can accumulate quickly.

## Physical Model

The simulation uses a **Schwarzschild black hole**, which represents a non-rotating, spherically symmetric black hole.

For simplicity, the particle is restricted to the equatorial plane. This removes the need to numerically evolve the polar coordinate and reduces the complexity of the system while retaining the essential physics of the orbital motion.

The event horizon occurs at the Schwarzschild radius:

[
r_s = 2M
]

because geometric units are used, with:

[
G=c=1
]

## Initial Conditions

The particle begins outside the event horizon with:

* An initial radius of (r=8M)
* No initial radial velocity
* A non-zero angular velocity

These conditions allow the simulation to explore how the initial motion determines the resulting trajectory.

By changing the initial conditions, different behaviours can be investigated, including:

* Bound or orbital trajectories
* Inward spiralling trajectories
* Capture by the black hole
* Escaping trajectories

## Output

The main output is a two-dimensional orbit plot showing the particle's trajectory around the Schwarzschild black hole.

The plot contains:

* **Particle trajectory** — the path calculated from the geodesic equations.
* **Black hole centre** — the central position of the black hole.
* **Event horizon** — the Schwarzschild radius surrounding the black hole.

An animation can also be used to visualise the particle's motion step by step.

## Purpose of the Notebook

This notebook serves as the **computational foundation** for the more advanced gravitational-lensing simulations in this project.

The same underlying idea — calculating how trajectories evolve in curved spacetime — can later be extended from ordinary particle orbits to **photon geodesics**, gravitational lensing, black-hole shadows, and comparisons with hypothetical traversable wormholes.

### Notebook Progression

**General Relativity → Geodesic Equations → Numerical Integration → Particle Trajectories → Photon Trajectories → Gravitational Lensing**

This notebook therefore acts as the starting point for the more advanced black-hole and wormhole simulations developed later in the project.
