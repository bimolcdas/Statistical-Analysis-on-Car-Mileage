STATISTICAL ANALYSIS ON CAR MILEAGE

DATA SET LINK:  
archive.ics.uci.edu/machine-learning-databases/auto-mpg/ 

Author:

Name: Bimol Chandra Das
Email ID: bdas23@my.trine.edu

INTRODUCTION  

Data set chosen:  
https://archive.ics.uci.edu/ml/machine-learning-databases/auto-mpg/ 

The dataset provides information on cars, including mileage in miles per gallon (mpg), number of cylinders, displacement, horsepower, acceleration, origin (Asia, America, or Europe), and car name. It consists of 400 rows and 8 columns. 

Why I chose this dataset:  
This dataset is appropriate for analysis due to its manageable size and structure. It addresses a common interest among car buyers and owners by enabling analysis of factors that impact car mileage, guiding buyers in making informed choices.

AIM:  
To identify the factors that most significantly affect car mileage and use this to improve mileage predictions.

Questions Addressed:  
1) Identify cars with the highest mpg.  
2) Determine the factors affecting car mileage.  
3) Identify the most influential factor.  
4) Analyze the percentage distribution by origin.  
5) Detect any anomalies in data distribution.

All descriptive analysis was conducted on the Anaconda platform, including calculations for mean, median, variance, standard deviation, and interquartile range, along with graphical representations.

PROCESSING/CLEANING THE DATA  

Data Cleaning involved:  
1) Filling missing values in the "weight" column using the median.  
2) Replacing missing qualitative values with “Data Unavailable.”  
3) Standardizing formats and removing outliers using box plots and Anaconda.  
4) Ensuring no car name repetitions in the data.

DESCRIPTIVE ANALYSIS  

Descriptive analysis was performed using Anaconda software with numpy, matplotlib, pandas, seaborn, and scipy.

Statistical Analysis of Numerical Columns:  
Statistics were calculated for mpg, cylinders, displacement, horsepower, weight, and acceleration. The dataset was analyzed for central tendencies and spread, and graphs were plotted to understand data distribution.

CONCLUSION  

The analysis provided insights into how car mileage varies with other factors such as the number of cylinders, displacement, acceleration, weight, and horsepower. The average mileage is around 23.5 mpg, and correlation and regression analyses can further reveal relationships between these factors.
