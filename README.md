# M.Tech-Thesis
•	Input Data/Input data to run example inversions and simulations
      o	SEA1shape.npy: The shape of the polygon around SEA1
      o	ch_catalog.csv: Swiss catalog from 1960 - 2024
      o	ch_rect.npy: The shape of a rectangle around SEA1
      o	example_catalog.csv: to be inverted by invert_etas.py
      o	example_catalog_mc_var.csv: to be inverted by invert_etas.py when varying mc mode is used
      o	magnitudes.npy: example magnitudes for mc estimation

•	congif/ configuration files for running the scripts in runnable_code/
      o	names should be self-explanatory
•	runnable_code/ scripts to be run for parameter inversion or catalog simulation
      o	estimate_mc.py: estimates constant completeness magnitude for a set of magnitudes
      o	invert_etas.py: calibrates ETAS parameters based on an input catalog (option for varying mc, and option to fix certain parameters available)
•	etas/ 
      o	here is where all the important functions algorithms are defined
•	output_data/
      o	output goes here.
