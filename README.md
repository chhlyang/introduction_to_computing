# Introduction to Computing

**Introduction to Computing** is a repository dedicated to exploring numerical methods and computational techniques through a series of interactive notebooks. The project is structured into three primary modules:

- **Global Approximation** (Updated as of February 25)
- **Initial Value Problems of ODEs** (Coming Soon)
- **Boundary Value Problems of ODEs** (Coming Soon)

All numerical experiments and demonstrations in this repository are implemented using [Julia 1.10.5](https://julialang.org/).

---

## Overview

This repository provides an in-depth exploration of computational methods in numerical analysis and differential equations. Each module is designed to guide you through theoretical foundations, practical implementations, and numerical experiments, enabling a comprehensive understanding of various computational techniques.

---

## Modules

1. **Global Approximation**  
   This module delves into methods for approximating the global behavior of functions—extending beyond simple interpolation. We analyze global errors and address the Runge phenomenon encountered with uniform grids, and we apply Chebyshev techniques to numerical integration and differentiation. *(Content updated as of February 25)*

2. **Initial Value Problems of ODEs**  
   In this upcoming module, we explore numerical techniques for solving initial value problems in ordinary differential equations. We begin with the Euler method, progress to higher-order Runge-Kutta methods, and ultimately develop efficient multistep schemes.

3. **Boundary Value Problems of ODEs**  
   This module investigates robust approaches for solving boundary value problems. Rather than relying solely on the shooting method, we introduce alternative discretization strategies, delve into Galerkin methods, and provide an overview of the Finite Element Method (FEM).

---

## Prerequisites

- **Julia 1.10.5**:  
  All notebooks and numerical experiments are based on Julia 1.10.5. Please ensure you have this version installed or a compatible version available.
  
- **Background Knowledge**:  
  A basic understanding of numerical analysis, differential equations, and computational methods is recommended to make the most out of this repository.

---

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/chhlyang/introduction_to_computing.git
   cd introduction_to_computing
