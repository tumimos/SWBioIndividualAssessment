# SWBioIndividualAssessment
This material was submitted for the SWBio Data Science and Machine Learning module (Jan2025).
This is an analysis script written in Python to assess the trends of the prevalence of Autism Spectrum Disorder as tracked by th the U.S. Centers for Disease Control and Prevention (CDC) Autism Spectrum Disorder pages (https://www.cdc.gov/autism/data-research/data-table.html). 

To run:
1.	Download a copy of the data table from https://www.cdc.gov/autism/data-research/data-table.html, which Is maintained and updated by the CDC, and save it as “autism_prevalence.csv”. Alternatively, Update the import command to match the name of the file on your machine. The script should be able to run with updated versions of the data file, on the condition that the column headers remain the same.
2.	Download and import the following modules;
a.	pandas as pd
b.	seaborn as sns
c.	matplotlib.pyplot as plt
d.	train_test_split fom sklearn.model
e.	LinearRegression from sklearn.linear_model
f.	PolynomialFeatures from sklearn.preprocessiong
g.	Pipeline from sklearn.pipeline
h.	GridSearchCV from sklearn.model_selection
i.	LinearGAM, a, f from pygam
j.	numpy as np
k.	mean_squared_error from sklearn.metrics
l.	scipy.stats as stats
3.	Run the script within the same folder as the data file to completion.
This analysis, based on the data as of December 2024, found that there is an increase in the number of publications estimating ASD prevalence between 1966 and 2022, with no significant difference in the estimated prevalences between countries.
