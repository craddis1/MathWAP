# MathWAP

Companion repository to  [*CosmoWAP*](https://github.com/craddis1/CosmoWAP) 

MathWAP contains Mathematica notebooks that computes the fourier power spectrum and bispectrum including contributions (up to second order) from wide-separation (WS) and relatativistic (GR) efects as well as primoridal non-Gaussianity (PNG).

See [*Documentation*](https://cosmowap.readthedocs.io/en/latest/overview.html) for full doumentation.

## Contents

### Kernels.nb

Defines redshift space kernels

### Power spectrum

See The_powerspectrum.nb: Main file used in computation exports terms into .json files

Uses:
- Pk_expansions.nb: Defines  the wide angle and radial evolution series expansions for the power spectrum

- Pkfuncsandrules.nb: Contains functions used in The_powerspectrum.nb (is messy and long - sorry i don't like mathematica)

### Bispectrum

See The_bispectrum.nb: Main file used in computation exports terms into .json files

Uses:
- expansions.nb: Defines  the wide angle and radial evolution series expansions for the bispectrum

- Bkfuncsandrules.nb: Contains functions used in The_bispectrum.nb (is messy and long - sorry i don't like mathematica)

## Outputs

Outputs are stored from mathematica in .json files in mathematica_expr - also read_mathematica.ipynb can be used for converting from mathematica to python formatting.

Terms for other kernels can also be provided or computed from the The_bispectrum.nb - format can also be flexible.


## Usage

Based on work in [arXiv:2407.00168](https://arxiv.org/abs/2407.00168) 

Also for PNG stuff please refer too: arXiv:24xx.xxxx
