# 3D Models for an Impact Detection System

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the 3D models for the experimental system developed for the undergraduate thesis: **"Določanje lokacije in sile udarca na plošči z uporabo nevronskih mrež"** (Impact Location and Force Identification on a Plate Using Neural Networks) by Enej Podlipnik.

## System Overview

The system is designed to measure the dynamic response of a 3D-printed plate to external impacts. It consists of a rigid support frame, a test plate, and four custom-designed piezoresistive sensors. The sensors are fabricated using multi-material 3D printing to effectively capture structural vibrations, which are then used as input for a deep learning model.

The complete source code for data acquisition and analysis can be found in the **[main project repository](https://github.com/podlen/Diploma_SourceCode.git)**.


## Files and Folders

-   **`/Source_Files`**: Contains the original CAD files created in SolidWorks (`.SLDPRT`, `.SLDASM`). These are intended for modification and further development.
-   **`/STL_Files`**: Contains the ready-to-print `.STL` files for all components, suitable for direct use with a 3D printer.

## How to Cite

If you use these models in your work, please provide attribution by citing this repository.

BibTeX format:

```bibtex
@misc{Podlipnik2025Models,
  author       = {Enej Podlipnik},
  title        = {3D Models for an Impact Detection System},
  year         = {2025},
  publisher    = {GitHub},
  journal      = {GitHub Repository},
  howpublished = {\url{https://github.com/podlen/3Dmodeli-zakljucna_naloga.git}}
}
```
