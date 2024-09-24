# MathWAP

Companion repository to  [*CosmoWAP*](https://github.com/craddis1/CosmoWAP) 

MathWAP contains Mathematica notebooks that computes the fourier power spectrum and bispectrum including contributions (up to second order) from wide-separation (WS) and relatativistic (GR) efects as well as primoridal non-Gaussianity (PNG).

## Contents

### Kernels.ipynb

Defines redshift space kernels

- expansions.nb: Defines series expansions for the wide angle and radial redshift parts

- bkfuncsandrules.nb: Contains functions used in The_bispectrum.nb (is messy and long - sorry i don't like mathematica)

- The_bispectrum.nb: Main file used in computation exports terms into .json files

Outputs are stored from mathematica in .json files in mathematica_expr - also read_mathematica.ipynb can be used for converting from mathematica to python formatting.

Terms for other kernels can also be provided or computed from the The_bispectrum.nb - format can also be flexible.


## Usage


Based on work in [arXiv:2407.00168](https://arxiv.org/abs/2407.00168) 

Also for PNG stuff please refer too: arXiv:24xx.xxxx
