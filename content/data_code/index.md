---
title: Data and code
summary: An environment of open source tools for ecosystem data and modelling
date: "2018-06-28T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---

I am committed to an Open Science Practice. With [my group](https://computationales.ethz.ch/), we're building an environment of open source tools for ecosystem data and modelling. This should empower the community to use latest methodological innovations, developed in our group. Here is a list of our most important contributions:

# Code

## [rpmodel](https://stineb.github.io/rpmodel/)

An implementation of the *P-model* for leaf-level acclimation of photosynthesis [Stocker et al., 2019 *GMD*](https://gmd.copernicus.org/articles/13/1545/2020/)). Implemented as an R package (fully in R). This is used as reference code for P-model implementations in other modelling frameworks and for experimental model development. For efficient time series simulations use its implementation within [rsofun](https://stineb.github.io/rsofun/).

[Website](https://stineb.github.io/rpmodel/)

[Code on CRAN](https://cran.r-project.org/web/packages/rpmodel/index.html)

[Development code](https://github.com/stineb/rpmodel/)

---

## [rsofun](https://stineb.github.io/rsofun/)

A modelling framework for site-scale simulations of ecosystem processes, implemented as an R package (back-end in Fortran 90). Implements the following models:

- *P-model* for leaf-level acclimation of photosynthesis, [Stocker et al., 2019 *GMD*](https://gmd.copernicus.org/articles/13/1545/2020/)
- *SPLASH* for bioclimatic variables, including the surface radiation budget and the soil water balance, [Davis et al., 2017 *GMD*](https://gmd.copernicus.org/articles/10/689/2017/gmd-10-689-2017.html)
- *LM3-PPA* for comprehensive simulations of ecosystem carbon and water cycling, tree growth, and tree cohort-explicit forest dynamics following the Perfect Plasticity Approximation, [Weng et al., 2015](www.biogeosciences.net/12/2655/2015/doi:10.5194/bg-12-2655-2015)

[Website](https://stineb.github.io/rsofun/)

[Code](https://doi.org/10.5281/zenodo.3759405)

[Development code](https://github.com/stineb/rsofun/)

---

## [ingestr](https://stineb.github.io/ingestr/)

Functions to extract (ingest) environmental point data from large global files or remote data servers and create time series at user-specified temporal resolution. Facilitates forcing and evaluation data preparation for [rsofun](https://stineb.github.io/rsofun/). The main functionalities are:

- Temporal downscaling from montly to daily resolution
- Quality filtering, temporal interpolation and smoothing of remote sensing data
- Handling of different APIs and file formats, returning ingested data in tidy format.

[Website](https://stineb.github.io/ingestr/)

[Code](https://doi.org/10.5281/zenodo.4495563)

[Development code](https://github.com/stineb/ingestr/)

---


## [SOFUN](https://stineb.github.io/sofun/)

A modular modelling framework for global-scale simulations of ecosystem processes, implemented in Fortran 90. . Implements the following models:

- *P-model* for leaf-level acclimation of photosynthesis, [Stocker et al., 2019 *GMD*](https://gmd.copernicus.org/articles/13/1545/2020/)
- *SPLASH* for bioclimatic variables, including the surface radiation budget and the soil water balance, [Davis et al., 2017 *GMD*](https://gmd.copernicus.org/articles/10/689/2017/gmd-10-689-2017.html)

[Website](https://stineb.github.io/sofun/)

[Code](https://doi.org/10.5281/zenodo.3529466)

[Development code](https://github.com/stineb/sofun)

---

## DYPTOP

A cost-efficient TOPMODEL implementation to simulate sub-grid spatio-temporal dynamics of global wetlands and peatlands ([Stocker et al., 2014 *GMD*](https://gmd.copernicus.org/articles/7/3089/2014/)). Written in Fortran.

[Development code](https://github.com/stineb/dyptop)

---

## cwd

A light R package for deriving cumulative water deficits, given time series of evapotranspiration and precipitation.

[Website](https://stineb.github.io/cwd/)

[Code](https://doi.org/10.5281/zenodo.5359053)

[Development code](https://github.com/stineb/cwd/)

---

## More code

More of my open source code and open access model outputs:

- [rbeni](https://github.com/stineb/rbeni): An eclectic collection of functions used in Beni's daily life, implemented as an R package.

---

# Data and outputs

- [fLUE](https://doi.org/10.5281/zenodo.1158524): Fractional reduction in light use efficiency due to soil moisture stress, estimated at FLUXNET2015 Tier 1 sites, as described in Stocker et al., (2018) *New Phytologist*.
- [SCWDX80 and zCWDX80](https://doi.org/10.5281/zenodo.5515246): Global rooting zone water storage capacity (SCWDX80, mm) and rooting depth (zCWDX80, mm) estimates from Stocker et al., (2021) *BiorXiv*.
- [GPP at FLUXNET Tier 1 sites from P-model](https://doi.org/10.5281/zenodo.3559850): Gross primary production, simulated by the P-model for each FLUXNET 2015 Tier 1 site. From stocker et al. (2020) *GMD*
