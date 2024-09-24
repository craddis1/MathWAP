# MathWAP

Companion repository to  [*CosmoWAP*](https://github.com/craddis1/CosmoWAP)
\mathematica_routines 

The_bispectrum.nb allows for the computation of wide separation terms for some given Fourier kernels (defined in kernels.nb). 2nd order wide-separation effects can be slow to compute due to huge number of terms involved.

- kernels.nb: Defines 1st and 2nd order kernels

- expansions.nb: Defines series expansions for the wide angle and radial redshift parts

- bkfuncsandrules.nb: Contains functions used in The_bispectrum.nb (is messy and long - sorry i don't like mathematica)

- The_bispectrum.nb: Main file used in computation exports terms into .json files

Outputs are stored from mathematica in .json files in mathematica_expr - also read_mathematica.ipynb can be used for converting from mathematica to python formatting.

Terms for other kernels can also be provided or computed from the The_bispectrum.nb - format can also be flexible.
