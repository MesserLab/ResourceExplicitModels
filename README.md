# Resource-Explicit Interaction Models for Spatial Populations

Models and data for "Resource-explicit interactions in spatial population models,"
https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.14432

Authors:
Samuel E. Champer, Bryan Chae, Benjamin C. Haller, Jackson Champer, Philipp W. Messer


## Contents:
Models are seperated into five folders.
- non-resource-explicit_models: contains models that are used for performance comparisons in the paper.
- hexagonally-tiled_models: contains versions of the four main resource-explicit model variants using a hexagonally tiled area.
- square-tiled_models: as above, but with a square tiled area.
- random_resource_placement_models: as above but with randomly placed resource nodes.
- other_resource_explicit_models: contains an additional version of the elastic model that has been optimized for a species with infrequent dispersal. This model uses a square tiling, but could also be implimented with a hexagonal tiling. This folder also contains versions of each of the four main resource-explicit model variants that have been altered to have a semi-fixed population size. These models use a square tiling, but could be implimented with any resource placement method.


#### Note: These models require a minimum of SLiM version 4.1, available at https://messerlab.org/slim/ or https://github.com/MesserLab/SLiM

[![DOI](https://zenodo.org/badge/593493308.svg)](https://zenodo.org/doi/10.5281/zenodo.13743327)
