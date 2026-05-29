# Gravitational Orbit Simulation using Euler's Method

🌍 Computational Physics project focused on simulating planetary motion under Newtonian gravity using Euler’s Numerical Method. The project investigates different orbital trajectories, energy conservation, angular momentum, and the effect of numerical step size on simulation accuracy.

---

## Topics Covered

- Gravitational Two-Body Problem
- Newton's Laws of Motion
- Euler's Numerical Method
- Circular, Elliptical, Parabolic and Hyperbolic Orbits
- Energy Conservation
- Angular Momentum
- Numerical Error Analysis
- Scientific Visualization

---

## Problem Overview

The gravitational potential is given by:

$$
V(r) = -\frac{4\pi^2}{r}
$$

which produces the central force:

$$
\mathbf{F} = -\frac{4\pi^2}{r^2}\hat{r}
$$

The equations of motion are solved numerically to study the trajectories of celestial bodies under gravity.

---

## Simulations Performed

### 1. Orbit Shape Analysis

Different initial velocities are used to generate:

- Circular Orbit
- Elliptical Orbit (Low Velocity)
- Elliptical Orbit (High Velocity)
- Parabolic Escape Orbit
- Hyperbolic Escape Orbit

The relationship between total energy and orbit shape is analyzed.

---

### 2. Step-Size Dependence

The effect of different Euler time steps is studied:

- dt = 0.01
- dt = 0.001
- dt = 0.0005

The simulation demonstrates how numerical errors accumulate and affect long-term orbital stability.

---

### 3. Energy Conservation Analysis

The total mechanical energy

$$
E = \frac{1}{2}(v_x^2+v_y^2)-\frac{4\pi^2}{r}
$$

is monitored throughout the simulation to measure numerical accuracy and energy drift.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Numerical integration of orbital motion
- Multiple orbit type visualization
- Energy conservation analysis
- Step-size error comparison
- Scientific plotting and simulation

---

## Key Observations

- Orbit shape depends entirely on the initial velocity.
- Circular and elliptical orbits occur for negative total energy.
- Parabolic and hyperbolic trajectories correspond to escape motion.
- Euler’s Method introduces energy drift, causing orbital paths to slowly spiral outward.
- Smaller time steps significantly improve numerical accuracy.

---

## Conclusion

This project demonstrates how numerical methods can be used to simulate gravitational systems and planetary motion. It highlights both the strengths and limitations of Euler’s Method while providing insight into orbital mechanics, conservation laws, and numerical stability.

---

## How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install dependencies:

```bash
pip install numpy matplotlib jupyter
```

Run the notebook:

```bash
jupyter notebook
```
