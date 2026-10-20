# Information Transduction with Multiple States

This repository contains the manuscript and (soon) the code for my Master's Thesis in **Physics of Data** at the University of Padua: *Information transduction with multiple states*.

## Overview

Biological and physical systems often need to extract information from a noisy, unobservable environment using a limited number of sensors, all while working under a strict thermodynamic energy budget. This project investigates how to optimize the internal sensory couplings to maximize the extracted information while keeping the relative thermodynamic cost constant.

Using Langevin dynamics, Stochastic Thermodynamics, and Partial Information Decomposition (PID), the study explores how architectural complexity dictates the optimal information-harvesting strategy.

## Key Findings

The system's topology fundamentally shifts the nature of the information extracted:

* **Many Sensors, One Environment (**$M=2, N=1$**)** $\rightarrow$ **SYNERGY**: When multiple membrane sensors monitor a single active bath, the optimal performance is achieved by maximizing the **synergistic** information shared between the sensors. The system exploits complementary observations to reconstruct the hidden state.

* **Few Sensors, Many Environments (**$M=1, N=2$**)** $\rightarrow$ **REDUNDANCY**: When a single membrane integrates signals from multiple distinct active baths, the system naturally favors **redundancy**. It filters out independent local noise by focusing on overlapping signals, establishing a robust macroscopic readout.

## Methods

* **Dynamics**: Multivariate Ornstein-Uhlenbeck processes (Langevin dynamics).

* **Information Theory**: Shannon Entropy, Mutual Information, Partial Information Decomposition (PID).

* **Thermodynamics**: Stochastic energetics, relative entropy production rate, and time-symmetric dynamical activity (Traffic $\mathcal{T}$).

## Author

**William Conte**
M.Sc. in Physics of Data, University of Padua (2025/2026)