# NEMO model outputs extractions by MEOM 

Here you can find and put the informations on where (which machine) to find the various extractions and computations done from the outputs of NEMO simulations produced by MEOM 

You can browse data by :
  - [simulations](simulations/README.md)
  - [region of interest](regions/README.md)
  - [platforms](platforms/README.md) 
  - [variables](variables/README.md)
  
To add a new dataset from a simulation you must know :
  - the configuration : CONFIG
  - the simulation : SIMU
  - the name of the extraction : REGION (with its coordinates)
  - the machines on which it is stored : PLATFORM
  
Here are the steps to add it in the catalog :
  - create a 'card' in the items directory : CONFIG-SIMU-VARIABLES-FREQUENCY-ALL-RELEVANT-INFOS.md (relevant infos are the ones that differ from another dataset)
  - add the link to the item you just created in :
      - simulations/CONFIG-SIMU.md, then add the link to it in CONFIG.md then add the simu to simulations/README.md if it is a new one
      - regions/REGION.md and add the region in regions/README.md if it is a new one
      - platforms/PLATFORM.md and add the platform to platforms/README.md if it is a new one

It looks like a lot but some of the links should already exist if another dataset with the same simulation or the same region or for the same platform already exists, so in this case just check ! If the dataset is available on multiple platforms, check for all the platforms of course.

If you create a 'card' for a new configuration please also add the 'card' for the corresponding grid files and try to plot the bathymetry like in [this notebook](regions/notebooks-maps/maps-eNATL60.ipynb).

If you create a 'card' for a new region please try to plot its area with a notebook like in [this notebook](regions/notebooks-maps/maps-eNATL.ipynb).
