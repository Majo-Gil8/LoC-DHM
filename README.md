# LoC-DHM

This repository contains the datasets and resources used in the manuscript:

**“Custom-Fabricated Microfluidic Lab-on-a-Chip Platform for Quantitative Phase Imaging with Off-Axis Digital Holographic Microscopy”**

---

## Overview

This repository provides experimental holographic datasets acquired using an off-axis Digital Holographic Microscopy (DHM) system combined with custom PDMS Lab-on-a-Chip (LoC) devices.

The data support the validation of the LoC platform for quantitative phase imaging (QPI), including biological analysis and micro-particle tracking.

---

## Repository Structure

- **LoC_CAD**: SolidWorks design files (.SLDPRT) of the Lab-on-a-Chip (LoC) devices used for fabrication. These files correspond to the microfluidic geometries that were 3D-printed and replicated in PDMS.

- **LoC_CAlbicans**: Digital holograms of *C. albicans* suspensions used for cell quantification experiments.

- **LoC_RBC**: Digital holograms of red blood cells (RBCs) used for quantitative phase validation and statistical analysis (TOST).

- **Tracking**: Holographic sequences of magnetic micro-composites used for 3D particle tracking under microfluidic flow.


The datasets were used to perform the analyses reported in the manuscript, including background phase characterization, biological sample evaluation, and particle tracking.

Specifically:

- The data in each folder directly correspond to the experiments described in the respective sections of the manuscript.  
- The holograms can be used to reproduce the quantitative phase imaging results and associated analyses.  

---

## Reconstruction Method

Digital hologram reconstruction and phase retrieval were performed using the methodology described in [1].

The datasets provided in this repository are compatible with this reconstruction framework, and users can apply the same methodology to reproduce the results presented in the manuscript.

---

## References

[1] Ortega Sanchez, Karina and Restrepo, René and Padilla Vivanco, Alfonso and Castaneda, Raul and Doblas, Ana and Trujillo, Carlos, Intricate Quantitative Phase Imaging Via Vortex-Legendre High-Order Phase Compensation. Available at SSRN: https://ssrn.com/abstract=5282404 or http://dx.doi.org/10.2139/ssrn.5282404
