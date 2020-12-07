# Distributed_Temperature_Sensing

Contact:
Johann S. Becker
University of Rhode Island
Department of Ocean Engineering Masters Student
beckerj@uri.edu

This is a living repository of Distributed Temperature Sensing (DTS) experiments. Includes: data, .ipynb analysis and related documentation, etc. as discussed in the site map below.

Hardware:

	DTS System:
		- An Silixa XT DTS was used for all Distributed Temperature measurements discussed in this 		repository. 

	Optical Fiber
		- A custom Fiber optic fishing line (FOFL) was use for all experiments currently discussed in 		this repository.
		- In future experiments: Cortland Ruggedized optical will be used as well.
		- Both are multimode fiber.

Site Map:

Available in this main folder:
	- Environmental Sensing using DTS: A list of relevant and interesting journal articles that have been 	read.
	- XTDTS_SamplingGuide: This document walks through the process of sampling using the Silixa 	XTDTS system. It covers software installation, configuration, sampling, data visualization and 		exporting, and hardware set up. 
	
The home experiments folder contains 3 experiments performed between November 30th and December 5th, 2020. Each experiment contains:
	- Description of the experimental set up, DTS configuration used, Experimental notes, and a brief 	explanation of the results. These documents are meant to put the data in context.
	- The raw temperature data collected 
	- Images related to the experiment.
	- Relevant other data and visuals

In the ipynb_scripts folder 3 folders with .ipynb scripts, the data need to run them, and resulting figures are included. 
	- Fiber Homogeneity finds the difference and percent difference between the temperature 			measurements along the fiber and a calibrated probe. 
	- Node Timeseries pulls the time series of selected nodes along the fiber and plots their 			temperature measurements as a function of time. 
	- Tank Profile takes a selected length range of the fiber and plots the temperature measurements as 	a vertical profile.