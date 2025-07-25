⚛️ Analysis of Particle Identification with a ΔE-E Telescope
📖 Project Overview
This repository contains the data analysis I performed for a particle physics experiment using a ΔE-E telescope setup. The main goal was to identify charged particles emitted from a  
241
 Am source by measuring their energy loss.

The method relies on the Bethe-Bloch formula. A particle first passes through a thin silicon detector (ΔE) and then stops in a thicker one (E). By analyzing the energy deposited in each, we can determine the particle's identity.

My Contribution 👨‍💻
For this project, I was responsible for all the data analysis and visualization. My specific tasks were:

Calibrating the detectors using the known alpha spectrum of  
241
 Am.

Writing Python scripts to fit the spectral data with Gaussian functions.

Calculating the thickness of the ΔE detector and the Mylar foils by numerically integrating the stopping power data.

Plotting the theoretical Bethe-Bloch curves for different particles to compare with our experimental data.

🛠️ Tools I Used
Python

NumPy

Matplotlib

SciPy

📊 Results and Analysis
Here are the key plots from my analysis, which show how the particles were identified.

1. Detector Calibration
First, I calibrated the E-detector to establish a relationship between the channel number and the particle energy in keV.

``

The calibrated spectrum for the E-detector. The main peak at 5485.34 keV matches the known primary alpha energy of  
241
 Am, confirming the calibration was accurate. ✅

2. Particle Identification with the Bethe-Bloch Formula
The core of the analysis was comparing the measured energy loss with the theoretical predictions.

``

Here, the experimental data points (blue) are plotted against the theoretical energy loss curves for various particles. As you can see, our data shows excellent agreement with the curve for alpha particles (orange line), while clearly differing from other particles like protons or lithium. 🎯

3. Final Confirmation of Particle Identity
To make the identification even clearer, I plotted the energy loss against ΔE⋅β 
2
 . This technique separates particles very effectively based on their mass and charge.

``

This plot provides the final confirmation. The measured data creates a distinct peak that lines up perfectly with the expected position for alpha particles, leaving no doubt about their identity. ✨

🏁 Conclusion
My analysis successfully identified the particles from the  
241
 Am source as alpha particles. The experimental data lined up very well with the predictions from the Bethe-Bloch formula, which validates the effectiveness of the ΔE-E telescope method for particle identification.
