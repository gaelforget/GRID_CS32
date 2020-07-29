
## GRID_CS32

[![DOI](https://zenodo.org/badge/199913320.svg)](https://zenodo.org/badge/latestdoi/199913320)

The included files define the global grid known as `CS32` which is used for unit testing the [MITgcm](http://mitgcm.org) / [ECCOv4](https://www.ecco-group.org) ocean modeling framework [Forget et al., 2015](http://www.geosci-model-dev.net/8/3071/2015/), [doi:10.5194/gmd-8-3071-2015](https://doi.org/10.5194/gmd-8-3071-2015)

- `grid_cs32.face00?.bin` files are the native grid files (model input; 2D split in 6 subdomains).
- `*.data` and `*.meta` files are the corresponding model output after adding vertical discretization and land mask (3D; global domain).

