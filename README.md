# CFD-Radial-Conduction-Analysis-Ansys
Steady-State Heat Conduction | ANSYS Fluent 2026 R1
<p align="center">

![ANSYS Fluent](https://img.shields.io/badge/Software-ANSYS%20Fluent%202026%20R1-red?style=for-the-badge)

![CFD](https://img.shields.io/badge/Domain-Computational%20Fluid%20Dynamics-blue?style=for-the-badge)

![Heat Transfer](https://img.shields.io/badge/Physics-Heat%20Transfer-orange?style=for-the-badge)

![Steady State](https://img.shields.io/badge/Analysis-Steady%20State-green?style=for-the-badge)

</p>

---

## 📖 Repository Overview

This repository presents a **2D steady-state Computational Fluid Dynamics (CFD)** simulation of **radial heat conduction through a solid annular geometry** performed using **ANSYS Fluent 2026 R1**.

The primary objective of this project is to investigate how thermal energy propagates through a cylindrical solid when a constant temperature difference is imposed between the inner and outer walls.

Although radial heat conduction is one of the fundamental heat transfer problems taught in engineering, CFD enables engineers to visualize the complete temperature field, quantify thermal gradients, and better understand conductive heat transfer beyond analytical calculations.

This project serves as a foundational exercise in **heat transfer modelling, numerical simulation, mesh generation, solver configuration, and post-processing within the ANSYS Fluent environment.**

---

> **Engineering Focus**
>
> Understanding radial heat conduction in cylindrical solids through numerical simulation and interpreting the resulting thermal behaviour using Computational Fluid Dynamics.

---

# 📑 Table of Contents

- [📖 Repository Overview](#-repository-overview)

- [🎯 Project Objectives](#-project-objectives)

- [📚 Engineering Background](#-engineering-background)

- [🌡️ Governing Physics](#️-governing-physics)

- [🧩 Geometry Creation](#-geometry-creation)

- [🕸️ Mesh Generation](#️-mesh-generation)

- [⚙️ Solver Setup](#️-solver-setup)

- [🧱 Material Properties](#-material-properties)

- [🚪 Boundary Conditions](#-boundary-conditions)

- [📉 Solution & Convergence](#-solution--convergence)

- [📊 Results & Post-Processing](#-results--post-processing)

- [🧠 Engineering Discussion](#-engineering-discussion)

- [✅ Validation](#-validation)

- [💡 Key Learnings](#-key-learnings)

- [🛠️ Skills Demonstrated](#️-skills-demonstrated)

- [📂 Repository Structure](#-repository-structure)

- [🚀 Future Improvements](#-future-improvements)

- [📚 References](#-references)

- [📄 License](#-license)

---

# ⭐ Repository Highlights

✔️ 2D Steady-State Heat Conduction

✔️ Radial Heat Transfer through an Annular Solid

✔️ ANSYS Fluent 2026 R1

✔️ Structured Quadrilateral Mesh

✔️ Second-Order Numerical Scheme

✔️ Engineering Interpretation of Temperature Distribution

✔️ Professional CFD Documentation

✔️ Recruiter-Friendly Project Presentation

---

## 📷 Repository Preview

> **Replace the image below with your final project cover image or temperature contour.**

<p align="center">

<img src="Images/Project_Cover.png" width="900">

</p>

---

## 📌 About This Repository

This repository is part of my Computational Fluid Dynamics learning portfolio, where I document simulation projects with an emphasis on the underlying engineering principles rather than simply presenting software outputs.

Each project is developed to strengthen my understanding of fluid mechanics, heat transfer, numerical methods, and engineering analysis while following professional documentation practices.


# 🎯 Project Objectives

This project was undertaken to develop a numerical understanding of **steady-state radial heat conduction** in a cylindrical solid using Computational Fluid Dynamics (CFD). While analytical solutions provide mathematical expressions for temperature distribution, CFD enables engineers to visualize thermal behaviour throughout the entire domain and better interpret the underlying heat transfer mechanisms.

The primary objectives of this study are:

- Investigate the radial temperature distribution within a 2D annular solid domain.

- Visualize conductive heat transfer resulting from a prescribed temperature difference between the inner and outer walls.

- Develop an understanding of thermal diffusion under steady-state conditions.

- Evaluate the influence of mesh quality on numerical accuracy and solution stability.

- Gain practical experience in geometry creation, meshing, solver configuration, and post-processing using **ANSYS Fluent 2026 R1**.

- Compare numerical results with the expected physical behaviour of radial heat conduction.

---

# 📚 Engineering Background

Heat transfer is one of the three fundamental modes of energy transport, occurring through **conduction, convection,** and **radiation**. In solid materials, thermal energy is primarily transferred by **conduction**, where heat flows from regions of higher temperature to regions of lower temperature due to molecular interactions.

One of the most common conduction problems encountered in engineering involves **radial heat transfer through cylindrical geometries**. Unlike one-dimensional planar conduction, the cross-sectional area available for heat transfer changes continuously with radius, resulting in a **non-linear temperature distribution** throughout the material.

Understanding this behaviour is essential in the design and thermal analysis of numerous engineering systems, including:

- Heat exchangers
- Steam and process pipelines
- Pressure vessels
- Boiler tubes
- Thermal insulation systems
- Nuclear reactor components
- Rotating machinery
- Aerospace propulsion systems

Although analytical solutions accurately predict temperature variation for idealized cases, they provide only mathematical results at discrete locations. Computational Fluid Dynamics complements these solutions by solving the governing energy equation over the entire computational domain, allowing engineers to visualize complete temperature fields, thermal gradients, and heat flow paths.

This project therefore serves as an introductory yet essential CFD study, bridging classical heat transfer theory with modern numerical simulation techniques.

---

# 🌡️ Governing Physics

The present analysis considers **steady-state heat conduction** through a homogeneous isotropic solid annulus.

The simulation is based on the following assumptions:

- Two-dimensional planar analysis
- Steady-state conditions
- Pure solid conduction
- No internal heat generation
- Constant thermophysical properties
- Homogeneous isotropic material
- Negligible thermal radiation
- Negligible convection within the solid domain

Under these assumptions, thermal energy is transferred exclusively by molecular conduction from the hotter inner surface toward the cooler outer surface until thermal equilibrium is established.

The governing physical mechanism is described by **Fourier's Law of Heat Conduction**, which states that heat flows in the direction of decreasing temperature and is proportional to the local temperature gradient.

As the simulation reaches convergence, the resulting temperature field represents the steady-state solution in which the rate of heat entering the annulus equals the rate of heat leaving it, satisfying the principle of conservation of energy throughout the computational domain.

---

## 💡 Engineering Significance

Although this problem appears mathematically simple, it forms the foundation for understanding far more complex thermal systems encountered in engineering practice.

The concepts explored in this project are directly applicable to:

- Thermal management of rotating machinery
- Heat exchanger tube analysis
- Insulation design
- High-temperature pressure vessels
- Nuclear fuel cladding
- Aerospace thermal protection systems
- Industrial piping networks

Mastering radial heat conduction through CFD provides a strong foundation for advanced simulations involving conjugate heat transfer, transient thermal analysis, and coupled fluid–thermal interactions.


















I welcome constructive feedback, discussions, and suggestions from the engineering community.
