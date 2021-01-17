# RAP-and-RUC-Soundings

This code was produced to aid in research of the environments of supercells as they cross the Appalchain Mountains. The code was used to gather RAP and RUC Data to calculate kinematic and thermodynamic parameters of inflow points of the supercells. All of thse files are in Jupyter Notebook using Python.

'Updated Sounding Code' file:
This file was used to siphon in RAP adn RUC model data from the NCEI Thredds server for a given point. Used MetPy and SharPy to calculate various paramerers. All that is needed to calulate and plot a sounding is the year, month, day, hour, latitude, and longitude. 

'Interpolate' file:
This file interpolates the sounding files created from the 'Updated Sounding Code' file so that all of the data is set at a uniform height. This will then be used to create composite soundings of all of the supercells at each given point. 

'Crossing Composite' and 'Non-crossing Composite' files:
This file takes in all the data created by the 'Interpolate' file and creates composite soundings for the crossing supercells and non-crossing supercells.
