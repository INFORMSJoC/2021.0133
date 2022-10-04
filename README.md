# 2021.0133

######Data files and scripts used in the article: Valeva, S., Pang, G., Schaefer, A.J. and Clermont, G., "Acuity-Based Allocation of ICU-Downstream Beds with Flexible Staffing."

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
