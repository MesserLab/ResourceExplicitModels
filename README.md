# Resource-Explicit Interaction Models for Spatial Populations

Models and data for the forthcoming "Resource-Explicit Interaction Models for Spatial Populations."

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
