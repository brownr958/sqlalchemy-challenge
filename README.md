# sqlalchemy-challenge

This repository contains the analysis of Hawaii's climate using a jupyter notebook and a Flask API
(written in Python). The following details the files within this repository:

Resources Folder- Contains all of the data using for this analysis including:
	1. hawaii.sqlite
	2. hawaii_measurments.csv
	3. hawaii_stations.csv

Images Folder- Contains the two saved images that were created using the jupyter notebook discussed below.
This folder contains:
	1. Precipitation.png
	2. tobs.png

Climate_notebook- This is a jupyter notebook that contains all of the analysis done in this repository and 
outputs the figures to the "Images Folder".

app.py- This is the file which contains code in order to produce a Flask web app. This application is able
query the climate data that is analyzed within the climate_notebook discussed above.