---
layout: default
---

# About Me

I am a **Affiliate Research Scientist at Space Science Institute** and a **Kavli Fellow at the Kavli Institute for the Physics and Mathematics of the Universe (Kavli IPMU)**, University of Tokyo. Previously, I was a postdoctoral researcher at **Lawrence Berkeley National Laboratory** and **Princeton University**.

My research connects **astrophysical simulations**, **machine learning**, and **statistical inference** to understand how structure emerges in the universe—from the intergalactic medium to galaxies and dark matter halos. I develop **differentiable, learnable simulation frameworks** that integrate data directly into the modeling process, allowing the universe itself to help refine our physical models.

I’m also deeply involved in educational outreach through *Splash* and [*Learning Unlimited*](https://www.learningu.org/about/), programs that empower university students to teach short, creative courses to local high school and middle school students. I’ve mentored and helped launch programs at UC Berkeley, UC Merced, Oxford University, Bard College, and Northwestern University.

---

# Current Research Focus

## 1. Reconstructing the Large-Scale Structure of the Universe

The distribution of matter—visible and dark—encodes the history of structure formation. I build **maximum-likelihood** and **differentiable** reconstruction methods to infer cosmic density and velocity fields from the *Lyman-α forest*, spectroscopic galaxy surveys, and the CMB.

- [Differentiable Cosmological Hydrodynamics for Field-Level Inference and High-Dimensional Parameter Constraints (2025)](https://arxiv.org/abs/2502.02294)  
- [Joint Cosmic Density Reconstruction from Photometric and Spectroscopic Samples (2025)](https://arxiv.org/abs/2311.18738)  
- [MAPLE: Band Power & Covariance Estimation of the 3D Lyα Forest Power Spectrum (2025)](https://arxiv.org/abs/2403.17294)  
- [CLAMATO DR2: First 3D Maps of the Detailed Cosmic Web at 2.05 < z < 2.55 (2022)](https://arxiv.org/abs/2109.09660)

These efforts powerfully constrain the evolution of cosmic structure and bridge early-universe initial conditions with present-day galaxy environments.

My main recent focus has been on differentiable hydrodynamics which would enable many new types of analysis including bayesian "field level" inference. This work is open source and [available on github](https://github.com/bhorowitz/DiffHydro_public); collaborators welcome!

<img src="https://github.com/bhorowitz/DiffHydro_public/blob/main/animations/diffhydro_rho_web.gif?raw=true" width="400" />

---

## 2. Machine Learning and Differentiable Simulations

I develop **GPU-accelerated, differentiable hydrodynamics** and hybrid physical–ML systems that plug directly into inference pipelines. These learnable simulations adapt their physics to observations, enabling self-correcting, data-driven astrophysics.

- [jFoF: GPU Cluster Finding with Gradient Propagation (2025)](https://arxiv.org/abs/2510.26851)  
- [BaryonBridge: Stochastic Interpolant Model for Fast Hydrodynamical Simulations (2025)](https://arxiv.org/abs/2510.19224)  
- [Differentiable Stochastic Halo Occupation Distribution (2024)](https://arxiv.org/abs/2211.03852)  
- [TensorFlow Hydrodynamics Analysis for Ly-α Simulations (2024)](https://arxiv.org/abs/2407.16009)  
- [HyPhy: Deep Generative Conditional Posterior Mapping of Hydrodynamical Physics (2022)](https://arxiv.org/abs/2106.12675)

These tools accelerate parameter inference and enable **end-to-end differentiable astrophysical modeling**, where cosmic structure formation can be jointly optimized with data.

---

## 3. Mapping Gas, Galaxies, and the Cosmic Web

Using tomography of the **Lyman-α forest**, I have reconstructed the three-dimensional cosmic web at redshifts *z ≈ 2–3*, revealing how intergalactic filaments feed forming galaxies.

- [Synergistic Density Reconstruction from Lyman-α Forest and Spectroscopic Galaxy Surveys (2021)](https://arxiv.org/abs/2007.15994)  
- [Improved Lyman-α Tomography using ORCA (2021)](https://arxiv.org/abs/2102.12306)  
- [TARDIS: Constrained Reconstruction of the z~2.5 Cosmic Web (2019)](https://arxiv.org/abs/1903.09049)

This work underpins the **cosmosTNG simulation suite** (Byrohl + Horowitz et al. 2025), which evolves observed initial conditions into full hydrodynamical realizations of the COSMOS field, enabling one-to-one comparison between simulated and real galaxies.

---

## 4. Linking Observations and Fundamental Physics

The same frameworks are being extended to probe the **Cosmic Microwave Background** and **Beyond-Standard-Model physics**, such as primordial black holes and dark matter interactions.

- [Reconstructing Small-Scale Lenses from the CMB (2019)](https://arxiv.org/abs/1710.10236)  
- [Cosmological Constraints from the Thermal Sunyaev-Zeldovich Power Spectrum (2017)](https://arxiv.org/abs/1609.01850)  
- [Revisiting Primordial Black Hole Constraints from Ionization History (2016)](https://arxiv.org/abs/1612.07264)

---

# Recent Projects and Collaborations

- [**cosmosTNG**](https://cbyrohl.de/en/project/cosmostng/) — Constrained hydrodynamical simulations of the COSMOS field.  
- [**Prime Focus Spectrograph (PFS)**](https://www.nao.ac.jp/en/research/project/pfs.html) — Galaxy Evolution Working Group, Large-Scale Structure Coordinator.  
- **CLAMATO Survey** — Principal developer of tomographic reconstruction framework and DR2 release.  
- [**Center for Data-Driven Discovery (CD³)**](https://cd3.ipmu.jp/), University of Tokyo  

---


<!--## Travel Calendar
<iframe src="https://calendar.google.com/calendar/embed?height=400&amp;wkst=1&amp;bgcolor=%23FFFFFF&amp;src=nnc2b9g4mr2f83dqgvkkh2km7s%40group.calendar.google.com&amp;color=%2342104A&amp;ctz=Asia%2FTokyo" style="border-width:0" width="600" height="400" frameborder="0" scrolling="no"></iframe> -->
