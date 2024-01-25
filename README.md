

# Instructions

This assignment is broken down into the following tasks:
Prepare the data.
Generate summary statistics.
Create bar charts and pie charts.
Calculate quartiles, find outliers, and create a box plot.
Create a line plot and a scatter plot.
Calculate correlation and regression.
Submit your final analysis.

#Files
Downloaded the files to help get started
Created jupyter notebook pymaceuticals.ipynb for pymaceuticals analysis.

#Before starting, 
run all the dependencies 
import matplotlib.pyplot as plt
import pandas as pd
import scipy.stats as st
import numpy as np
from scipy.stats import linregress

Read  downloaded csv files 
mouse_metadata_path = "data/Mouse_metadata.csv"
study_results_path = "data/Study_results.csv"

Read the mouse data and the study results
mouse_metadata = pd.read_csv(mouse_metadata_path)
study_results = pd.read_csv(study_results_path)
#Merge the both csv files 

 pymaceutical_complete = pd.merge(mouse_metadata, study_results, how="left", on=["Mouse ID", "Mouse ID"])

# Display the data table for preview in the dataframe

pymaceutical_complete

# Start analysis.
All analysis are in pymaceuticals. ipynb jupyter notebook.

# Hints and Help

Taken into consideration all the hints. I completed pynmaceuticals-challenge projects by consulting data-visualization documentation, 
went through all class materials and took  help from xpertlearning.

I encountered some difficulties in getting answer, but I did take time and study dependencies and did some reaserch.
    
   
     




