Detecting-Spatiotemporal-Clustering-of-COVID-19-in-the-United-States
Author: Fangzheng Lyu
Contact: flu8@illinois.edu

This dataset contains all the code, notebooks, datasets used in the study conducted for the research Multi-scale CyberGIS Analytics for Detecting Spatiotemporal Patterns of COVID-19 Data. Specifically, the dataset and the codes conducted a spatial-temporal analysis with space time kernel estimation with COVID-19 data. The dataset includes codes, notebook and example LiDAR data for the users to be able to find pattern and conduct analysis with COVID-19 data.


This dataset includes:
●	`STKDE` is a folder containing all codes and data used for Space time kernel density estimation
	○	`files` is a folder containing the data and parameter configuration
		■	`new_data.txt` contains all county level COVID-19 data from New York Times GitHub COVID-19 repository
		■	`new_parameterFile.txt` contains the parameters needed for space time kernel density estimation
	○	`kde.py` is a python-based code used to conduct STKDE
	○	`main.py` and `setting.py` is used to conduct STKDE onto COVID-19 data
●	`Clustering` is a folder containing all codes and data used for postprocessing and further analysis based on the result from space time kernel estimation 
	○	`change projection.ipny` is used to change the project of the spatial data
	○	`county.txt` and `us-counties.csv` include the information about counties in US
	○	`final_stkde.txt` is output of the STKDE algorithm.
	○	`correlation_stkde.txt` and `rt_new.txt` is used for conducting correlation analysis
	○	`data_processing.ipny` is a notebook used for processing the STKDE result
	○	`figure notebook1.ipny` and `figure notebook2.ipny` are used to generate figures used in the manuscript
