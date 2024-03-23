# Exploratory-Data-Analysis-(EDA)
This repository contains Python code for analyzing the dataset, including exploratory data analysis (EDA),preprocessing and visualization.

## Overview
Exploratory data analysis is used to analysis and investigating datta set ans summarize the main characteristic, often
visualization methods.i have done an EDA of a a dataset of employees working in ABc in company.

## Contents

myexcel.xlsx : excel file containing the ABC company  dataset.

Exploratory Data Analysis.ipynb: Jupyter Notebook containing Python code for data analysis.

README.md : This file providing an overview of the project.

### Link to the dataset:
 https://docs.google.com/spreadsheets/d/1VP9BE_eI2yl6uUHSm4mGiiwjRdoqCqnkcIjsv5Q2ex4/edit?usp=share_link


## Analysis

 ### 1.Import all necessary modules

  1.numpy

  2.pandas

  3.matplotlib

  4.seaborn

  import all libaries which required for data analysis and visualization

  ### 2.Reading data set

   The pandas libary offers wide range of possibilities  for loading data into the pandas dataframe like
   csv,xlxs,sql,html etc...our dataset is excel,read_excel  function used to load the dataset to pandas

  ### 3.Data preprocessing

    The main goal of data understanding is to gain general insights about of the data,which 
    covers the numbers of rows and columns,values in the data,data types and missing values 
    in the dataset.
    
    info(): Utilized the info() method to  print summary of dataset and identify missing values across
    the dataset.

    fillna(): method to impute missing values
    
    descibe():It provides summary statistics for numerical columns in the DataFrame, such as count,
    mean, standard   
    deviation,minimum, maximum, and quartiles.

    duplicate(): identify and remove any duplicate rows to ensure data integrity and prevent 
    based analysis. 

  
  ### 4. Exploratory Data Analysis (EDA)

     overview of the exploratory data analysis conducted on the dataset. Include insights gained from:

     the distribution of employees across each team and calculate the percentage split relative to 
     the total number of employees.

      Segregate employees based on their positions within the company.
      
      Identify the predominant age group among employees. 
      
      Discover which team and position have the highest salary expenditure.
      
      Investigate if there's any correlation between age and salary, and represent it visually. 

  
 ### 6.Data visualization

 Data visualization: Describe the visualizations created to explore relationships and patterns in the data.
 barplot, scatter plots,pie chart,pairplot are used  to visualize the my finding effectively
  
  
  ### 7. Note
  
  this is a fictional dataset used strictly for to demonstrate beginner data analysis skills. The results are not 
  official and should not be used to conclude actual relationships between the variables listed in ABC company 
  dataset.

  
