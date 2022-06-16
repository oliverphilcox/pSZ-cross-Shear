# pSZ-cross-Shear
This repository contains Python code implementing the polarized Sunyaev-Zeldovich (pSZ) and galaxy shear power spectra discussed in [Philcox+22](https://arxiv.org/abs/2206.07054). The main contributions are sourced by:
- Weak lensing (shear; scalars and tensors)
- Intrinsic alignments (shear; scalars and tensors)
- The Integrated Sachs-Wolfe effect (pSZ; scalars)
- The Sachs-Wolfe effect (pSZ; scalars)
- Doppler shifts (pSZ; scalars)
- Gravitational waves (pSZ; tensors)
- Noise (pSZ and shear)
We include Fisher forecasts for the pSZ and shear auto- and cross-power spectra, allowing the detectability of various components to be assessed.

Two main notebooks are included: the [first](3j%20Manipulations.ipynb) computes an array of 3j symbols needed for the pSZ noise curves using Julia, and the [second](pSZ%20x%20Lensing.ipynb) contains the main forecasting code in Python. We additionally include a [third](kSZ%20x%20Lensing.ipynb) notebook forecasting the detectability of kSZ cross-correlations.

### Authors
- [Oliver Philcox](mailto:ohep2@cantab.ac.uk) (Princeton / IAS)
- [Matt Johnson](mailto:mjohnson@perimeterinstitute.ca) (York / Perimeter)
