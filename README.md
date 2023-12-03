# Matplotlib Challenge

# Pymaceuticals Analysis

#### Overview:
A complete data set from a most recent animal study is provided. 
In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. 
The purpose of this study is to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

#### Datasets
2 datasets provided are 'Mouse Metadata' and 'Study Results'.

The key fields provided in 'Mouse Metadata' are "Mouse ID","Drug Regimen","Sex","Age_months","Weight (g)".

The key fields provided in 'Study Results' are "Mouse ID", "Timepoint", "Tumor Volume (mm3)","Metastatic Sites".

#### Data Preparation and Cleanup
2 datasets provided were combined based on 'Mouse ID' field.
A datacleanup was performed to remove the duplicate mouse id

#### Summary Statistics
A summary statistics was created which calculated the mean, median, variance, standard deviation, and SEM of the tumor volume for each regimen. 'Ramicane' regimen showed the lowest mean tumor volume followed by 'Capomulin' regimen.

#### Bar Chart
A bar chart was drawn to look at '# of Observed Mouse Timepoints' for each regimen. 

#### Pie Chart
A pie chart was drawn to look at the male vs female partipants in the study. It was observed that the male to female participant percentage was 51% and 49% respectively.

#### Box Plots
A box plot was drawn to analyze the final tumor volume observed for 4 different regimes. Again 'Ramicane' and 'Capomulin' regimes showed the lowest observed final tumor volumes.

#### Line Plot
A line plot was drawn to analyze the tumor volume of a particular mouse taking Capomulin regime over the period of study. It was osberved that the final tumor volume has gone down over the period of the study.

#### Scatter plot
A scatter plot was drawn to analyze mouse weight vs. the average observed tumor volume. It was obsereved that the average observed tumor volume goes up with the mouse weight

#### Correlation and Regression
The correlation coefficient and a linear regression model for mouse weight and average observed tumor volume for the entire Capomulin regimen was calculated.
The correlation between mouse weight and the average tumor volume is 0.84

## Files
* Source Code - Pymaceuticals/pymaceuticals_starter.ipynb
* Data Sets
  *   Pymaceuticals//data/Mouse_metadata.csv
  *   Pymaceuticals/data/Study_results.csv

## Run Instructions
* Open a terminal
* Confirm condo version\
  conda --version\
* Confirm jupyter version\
  jupyter --version\
* Activate conda environment\
  conda activate dev\
* Launch Jupyter Notebook\
  jupyter notebook\
* Jupyter Notebook is opened in a browser
* Open "Pymaceuticals/pymaceuticals_starter.ipynb" file using Jupyter Notebook
* Click on 'Cell > Run All' to run

