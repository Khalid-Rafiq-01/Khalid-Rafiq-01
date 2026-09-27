# Hi, I'm Khalid Rafiq 👋

I am a PhD student in Mechanical Engineering at the University of Nevada, Reno, working at the intersection of **machine learning, fluid dynamics, and scientific computing**.

My research focuses on learned reduced models for complex physical systems, particularly how the formulation of the learning problem shapes what a model can subsequently **generate, forecast, and control**.

My current work includes:

- Generative modeling of turbulent flows
- Representation learning for multiscale physical fields
- State-to-state evolution operators for parametric PDE forecasting
- Data-driven surrogate modeling for plume evolution
- Latent-space feedback control of unsteady fluid flows

## Current Research Themes

### Generative modeling for physical systems

I study how diffusion models, flow matching, and latent generative models can reproduce physically meaningful turbulent flow fields, with particular interest in preserving multiscale structure during compression and generation.

### Learned evolution operators for PDE forecasting

I develop encoder–propagator–decoder models that learn finite-time state-to-state evolution maps for parametric dynamical systems, enabling forecasts from arbitrary reachable states and variable time horizons.

### Learned representations for flow control

I use representation learning, clustering, and optimization to identify recurring flow regimes and dynamically accessible pathways for feedback control of unsteady fluid systems.

## Selected Research Projects

### Latent Operator Models for Parametric PDE Evolution

State-to-state latent surrogate models for transient parametric PDEs.

- [Latent Evolution Operator (LEO)](https://github.com/Khalid-Rafiq-01/Latent-Evolution-Operator-LEO-) — finite-time state-to-state forecasting from arbitrary intermediate states, physical parameters, and forecast horizons.
- [ConvLEO](https://github.com/Khalid-Rafiq-01/ConvLEO) — wind-conditioned plume forecasting from a single observation and a user-specified time jump.

### Deep Generative Models for Physical Systems

Generative modeling and representation learning for scientific data.

- [DDPM vs Flow Matching on MNIST](https://github.com/Khalid-Rafiq-01/diffusion-vs-flow-matching-mnist) — controlled comparison of diffusion and flow matching using identical U-Net backbones.
- Spectrally regularized latent flow matching for turbulence generation — under review.

### Latent Control of High-Dimensional Dynamical Systems

Reduced representations for identifying and controlling nonlinear fluid-dynamical pathways.

- [Cluster-based feedback control of separated-flow transients in a learned latent space](https://github.com/Khalid-Rafiq-01/cluster_based_latent_flow_control) — VAE-based latent macrostates and continuous cluster-aware feedback for controlling deeply separated flow over a stalled airfoil.
