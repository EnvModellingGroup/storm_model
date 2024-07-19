# Storm model template

This repo sets-up a standard storm model as used by the group for a project.

Description of directories:
- data: put your rasters, gauge data, tidal forcing data, ERA5 forcing, etc in here.
- mesh: put your shapefiles for meshing, rst files, .geo files and of course, your mesh here
- sims: put all of your model runs in here. Use a different directory for each set-up
- scripts: a bunch of scripts for analysing and visualising your model run

Note there is no `sims/base_case/storm_model_cont.py` file as checkppinting for wind-tide simulations
results in spurious results. 
