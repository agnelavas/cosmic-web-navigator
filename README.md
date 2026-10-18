# 3D Cosmological Web & Dark Matter Filament Navigator

An interactive WebGL 3D simulation and topological visualization modeling the large-scale filamentary structure of the universe, Zel'dovich pancake gravitational collapse, and cosmic void networks across 250 h⁻¹ Mpc cosmological volumes.

---

## Cosmological & Physical Principles

### 1. Jeans Gravitational Instability & Perturbation Growth
Large-scale cosmic structure originates from primordial density fluctuations growing in an expanding Friedmann-Lemaître-Robertson-Walker (FLRW) metric:
$$\frac{\partial^2 \delta}{\partial t^2} + 2H(t)\frac{\partial \delta}{\partial t} = 4\pi G \bar{\rho}_m \delta$$

### 2. Zel'dovich Anisotropic Collapse Approximation
Matter collapses sequentially along principal strain axes:
$$\mathbf{x}(\mathbf{q}, t) = \mathbf{q} - D(t) \nabla \Phi_0(\mathbf{q})$$
Producing 2D sheets (pancakes), 1D filaments, and 0D virialized cluster nodes.

### 3. Cosmic Web Topology (Betti Numbers)
Persistent homology classifies structure across density thresholds via topological Betti numbers ($\beta_0$ clusters, $\beta_1$ filament loops, $\beta_2$ cosmic voids).

---

## Live WebGL Deployment
Explore the live cosmic web:
**[https://agnelavas.github.io/cosmic-web-navigator/](https://agnelavas.github.io/cosmic-web-navigator/)**

---

## Local Execution
```powershell
python -m http.server 8002