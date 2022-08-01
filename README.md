# Unit 5 Homework: The Power of Plots
## Background

 Pymaceuticals Inc. is a new pharmaceutical company that specializes in anti-cancer pharmaceuticals. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

Access was given to he complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 

This document contains list of tables and figures needed for the technical report of the study along with a summary of observations. 

### Sample of Data 

<img width="608" alt="image" src="https://user-images.githubusercontent.com/75756974/182083169-42d9f172-62e3-42d1-97b7-345696f7f971.png">

#### 
Duplicates information contained within this data was removed 
<img width="617" alt="image" src="https://user-images.githubusercontent.com/75756974/182083448-60a3cc10-befe-458b-ac6e-33dea59fcc5c.png">


### Generate Summary Statistics

Create two summary statistics DataFrames:


<img width="680" alt="image" src="https://user-images.githubusercontent.com/75756974/182083621-1c3368fa-604e-4fe6-a429-9f4ac9a69a45.png">

 
 <img width="391" alt="image" src="https://user-images.githubusercontent.com/75756974/182083683-dba03cbb-b367-4394-8c2e-74b7e07f1748.png">


### Create Bar Charts and a Pie Charts

1. Generate two bar plots. Both plots should be identical and show the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.

    * Create the first bar plot by using Pandas's `DataFrame.plot()` method.


<img width="429" alt="image" src="https://user-images.githubusercontent.com/75756974/182083758-b55b21dd-3665-4a6d-acd9-dad57e0b2f2f.png">

    * Create the second bar plot by using Matplotlib's `pyplot` methods.
<img width="369" alt="image" src="https://user-images.githubusercontent.com/75756974/182083887-d680702a-922a-41fb-a184-621a37fc31e7.png">


2. Generate two pie plots. Both plots should be identical and show the distribution of female or male mice in the study.

    * Create the first pie plot by using both Pandas's `DataFrame.plot()`.
    <img width="251" alt="image" src="https://user-images.githubusercontent.com/75756974/182084088-4a38ca93-b49f-47ed-b81a-901988e36f17.png">


    * Create the second pie plot by using Matplotlib's `pyplot` methods.
    <img width="274" alt="image" src="https://user-images.githubusercontent.com/75756974/182084146-69af1e4b-2790-433d-99f0-7bbbd0306e67.png">


### Calculate Quartiles, Find Outliers, and Create a Box Plot 

1. Final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
    <img width="658" alt="image" src="https://user-images.githubusercontent.com/75756974/182084440-d2d804d8-cc01-4911-b861-7e40e4b62dfc.png">

*Potential outliers across all four treatment regimens is as follows

<img width="554" alt="image" src="https://user-images.githubusercontent.com/75756974/182084636-fb68fc22-28e2-4520-8527-ceb4cf1bced2.png">

2. Using Matplotlib, a  box plot of the final tumor volume was generated for all four treatment regimens. 
  
  <img width="398" alt="image" src="https://user-images.githubusercontent.com/75756974/182084907-07401d9e-7c8c-4aa7-b33d-c6ccf61613ba.png">


### Create a Line Plot and a Scatter Plot

1. Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.
<img width="603" alt="image" src="https://user-images.githubusercontent.com/75756974/182085621-8b28953b-1082-4488-91ca-de157e038af4.png">
<img width="603" alt="image" src="https://user-images.githubusercontent.com/75756974/182085512-4aae0b1b-9338-4df7-b14f-dbf52fec765c.png">

2. Generate a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.
<img width="413" alt="image" src="https://user-images.githubusercontent.com/75756974/182085695-0c1c32d6-d31f-44b5-9eba-be8f5d532459.png">


### Calculate Correlation and Regression

Correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment along with the linear regression model on top of the previous scatter plot.

<img width="504" alt="image" src="https://user-images.githubusercontent.com/75756974/182085809-8ce65d5a-e8ab-42d3-b873-e53b299ae7bb.png">

