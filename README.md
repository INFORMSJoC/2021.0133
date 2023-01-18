# 2021.0133

[![INFORMS Journal on Computing  Logo](https://INFORMSJoC.github.io/logos/INFORMS_Journal_on_Computing_Header.jpg)](https://pubsonline.informs.org/journal/ijoc)

This archive is distributed in association with the [INFORMS Journal on
Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data
that were used in the research reported on in the paper 
[Acuity-Based Allocation of ICU-Downstream Beds with Flexible Staffing](https://doi.org/10.1287/ijoc.2022.1267) 
by Valeva, S., Pang, G., Schaefer, A.J. and Clermont, G. 

## Cite

To cite this software, please cite the [paper](https://doi.org/10.1287/ijoc.2022.1267) using its DOI and the software itself using the following DOI.

[![DOI](https://zenodo.org/badge/10.5281/zenodo.7194693.svg)](https://zenodo.org/badge/10.5281/zenodo.7194693.svg)


Below is the BibTex for citing this version of the code.

```
@article{ICUdata,
  author =        {S. {Valeva}, G. Pang, A.J. Schaefer and G. Clermont},
  publisher =     {INFORMS Journal on Computing},
  title =         {Acuity-Based Allocation of ICU-Downstream Beds with Flexible Staffing},
  year =          {2022},
  doi =           {10.5281/zenodo.7194693},
  note =           {https://github.com/INFORMSJoC/2021.0133}
}  
```


###### Data
Contains instance and input files.
- admit: containts average arrivals per unit per day
- Instance26weekHighDemand; Instance26weekLowDemand; Instance26weekMedDemand: contain arrival data and ready to discharge patients by unit and day over
- Newtork28_2; Network28; Network37; Network60: contain the four network topologies used as examples in the paper
###### Scripts
Contains the python notebooks used to run the simulations in the paper.
- graphs: contains the script to generate the graphs in the paper
- sim_acuitybased: contains the script for the simulation using the acuity-based policy 
- sim_determ: contains the script for the simulation using the deterministic policy 
- sim_nonprob: contains the script for the simulation using the nonprobabilistic acuity-based policy
- sim_rmi: contains the script for the simulation using the ramdomized most idle policy
- sim_static: contains the script for the simulation using the static policy
