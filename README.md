[![DOI](https://zenodo.org/badge/265254045.svg)](https://zenodo.org/doi/10.5281/zenodo.10442485)

# yoon-etal_2025_naturewater

**The persistence of groundwater depletion in the United States across widely ranging futures**

Jim Yoon<sup>1\*</sup>, Stephen Ferencz<sup>1</sup>,  and Travis Thurber<sup>1

<sup>1 </sup>Pacific Northwest National Laboratory, Richland, WA, USA.

\* corresponding author:  jim.yoon@pnnl.gov

## Abstract
Groundwater resources are essential for crop production, enabling irrigation in many arid regions of the world. With a growing dependence on groundwater to serve increasing crop demands, concerns have been raised regarding alarming rates of groundwater depletion at the global scale. Modeling efforts focused on projecting future groundwater depletion have been limited by key factors: exogenous assumptions of human demand for groundwater that are unresponsive to changing groundwater availability and cost, simplistic treatment of the physics of groundwater depletion, narrow application to localized contexts, and limited exploration of future uncertainties. To address these gaps, we introduce a new coupled human-natural modeling approach for process-rich, broad-exploration of groundwater depletion futures, initially deployed for the continental United States. Our results indicate persistent groundwater depletion across a range of hydrologic-economic futures, with many of the key agricultural regions of the U.S. encountering substantial depletion even in the absence of adverse hydrologic or economic change.

## Journal reference
TBD

## Code reference
1. Jim Yoon, Stephen Ferencz, & Travis Thurber. https://github.com/jimyoon/farm_gw_sensitivity/

## Data reference

### Input data
2. Jim Yoon, Stephen Ferencz, & Travis Thurber. To be made available via MSDLIVE https://doi.org/10.57931/2565944

### Output data
3. Jim Yoon, Stephen Ferencz, & Travis Thurber. To be made available via MSDLIVE https://doi.org/10.57931/2565944

Human, I.M. (2021). My output dataset name [Data set]. DataHub. https://doi.org/some-doi-number

_your output data references here_


## Contributing modeling software
| Model             | Version | Repository Link | DOI                 |
|-------------------|---------|-----------------|---------------------|
| farm_gw_depletion | v1.0.0  | https://github.com/jimyoon/farm_gw_sensitivity/ | TBD                 |

## Reproduce my experiment

1. Run the `farms_gw_future_3Dsurface_HPC.py` from __[1]__ in a high performance computing environment (current simulations were deployed on PNNL's Deception HPC)
2. Step __1__ produces a consolidated csv file with results for all scenario/parameter combinations. These are made available in the `raw_outputs` folder of __[3]__

## Reproduce my figures
Use the scripts found in the `figures` directory to reproduce the figures used in this publication.

| Figure Number(s) | Script Name | Description | How to Run |
|  | --- | --- | --- |
| 1 | Conceptual Model Diagram - Manually generated in Powerpoint; Map of grid cells generated in QGIS |
| 2, 3, 4 | `grid_cell_depletion_post_process.py` from __[1]__ | Figs 2-4 developed through running model output through Python script, spatial joining to grid cells visualization in QGIS, and final touchups in Inkscape  |

