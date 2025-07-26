# ⚛️ Analysis of Particle Identification using a ΔE-E Telescope
## 📖 Project Overview
This repository documents the data analysis for a particle physics experiment utilizing a ΔE-E telescope apparatus. The primary objective of the experiment was to identify charged particles emitted from a ²⁴¹Am source by measuring their characteristic energy loss.


The methodology is predicated on the principles of the Bethe-Bloch formula, which describes the energy loss of charged particles traversing matter. In this configuration, a particle first passes through a thin silicon detector (which measures the energy loss, ΔE) and subsequently comes to a complete stop within a thicker detector (which measures the residual energy, E). An analysis of the energy deposited in each detector enables the definitive identification of the particle.


## Summary of Contributions 👨‍💻
## 🛠️ Methodology and Tools

The analysis was The author was responsible for the comprehensive data analysis and the generation of all associated visualisations. The specific tasks performed include
* The calibration of the detectors, which was accomplished by correlating their output signals with the known alpha particle emission spectrum of ²⁴¹Am.
* The development of Python scripts to perform Gaussian fitting on the spectral data, thereby determining precise peak energies.
* The calculation of the ΔE detector thickness and the thickness of several Mylar foils, which involved the numerical integration of standardized stopping power data.
* The generation of theoretical Bethe-Bloch curves for a range of particle types to serve as a basis for comparison with the empirical data.

## Conducted using the following software and libraries:
* Python
* NumPy: Utilized for numerical operations and array manipulation.
* Matplotlib: Employed for the generation of all graphical representations.
* SciPy: Used for statistical analysis, including curve fitting algorithms.

## Results and Analysis

The following sections present the key graphical results from the analysis, which collectively demonstrate the successful identification of the incident particles.
