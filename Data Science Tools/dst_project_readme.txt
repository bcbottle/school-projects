# TOOL1_FINAL_PROJECT
Repository for DST1 Fall 2023 Quarter Final Project

Repository contains all files for my final project for DST1 Fall 2023 quarter. 

_________________________________________________________________________________
CODEBOOKS
_________________________________________________________________________________

load_data.ipynb: This contains the code to initally load the datasets.
  Inputs: food_access_2019.csv
  Outputs: census_df.pkl, status_df.pkl, grad_df.pkl, food_df.pkl

edu_data_cleaning.ipynb: This contains the code for joining and cleaning the 3 school realted datsets.
  Inputs: census_df.pkl, status_df,pkl, grad_df.pkl
  Outputs: edu_df.pkl

food_access_cleaning: This contains the code for cleaning the food access data and joining it to the education data. 
  Inputs: food_df.pkl, edu_df.pkl
  Outputs: final_df.pkl

data_analysis.ipynb: This contains final code for analysis of data.
  Inputs: final_df.pkl
_________________________________________________________________________________
DATA FILES
_________________________________________________________________________________
education_datasets.zip
  census_df.pkl
  status_df.pkl
  grad_df.pkl

food_datasets.zip
  food_access_2019.csv
  food_df.pkl

joined_datasets.zip
  edu_df.pkl
  final_df.pkl

_________________________________________________________________________________
DATA SOURCES
_________________________________________________________________________________

Urban Institue Education Data Portal: https://educationdata.urban.org/documentation/schools.html#overview
USDA Food Research Atlas : https://www.ers.usda.gov/data-products/food-access-research-atlas/
EDFacts: https://www2.ed.gov/about/inits/ed/edfacts/data-files/index.html 

