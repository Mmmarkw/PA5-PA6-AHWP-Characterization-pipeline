# PA5-PA6 AHWP Characterization pipeline

Python analysis pipeline developed for broadband characterization of
achromatic half-wave plates used in CMB polarization instrumentation.

## Overview

The pipeline processes co-polarized and cross-polarized terahertz
transmission measurements across HWP rotation angles and frequency.

It includes:

- measurement discovery and validation
- frequency interpolation
- relative-gain correction
- normalized polarization response construction
- fourth-harmonic Fourier fitting
- modulation-efficiency extraction
- polarization-phase extraction
- fit diagnostics and uncertainty estimation
- comparison with optical models

## Tools

Python, NumPy, Pandas, Matplotlib

## Data

The raw experimental data and project-specific instrument interface are not distributed with this repository.
