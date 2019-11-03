# IT-Trends

### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [Files](#files)
4. [Results](#results)
5. [Licensing](#licensing)



## Installation <a name="installation"></a>
The workbook (IT Trends.ipynb) should run best with Python 3.*. and in a Jupyter notebook.
Libraries used are all standard in the Anaconda distribution (pandas, numpy, scikitlearn, seaborn and matplotlib)

## Motivation <a name="Motivation"></a>
I was interested into analyzing the recent changes in the IT industry. For that purpose I was analyzing and comparing the questionary results conducted by Stackoverflow. 
In its 1st part, the work compares the change in share of different job positions of the IT industry, between years 2013 and 2018.
Also it was shown how the popularity of different programming languages has evolved between these years.

In the 2nd part I focus only on the most recent 2018 data and try to find out which factors are best in explaining the salaries in the IT industry.

The data is cleaned but not all features are used. Therefore there is room for further analyzing and model improvement.

## Files <a name="Files"></a>
Attached is one python notebook file containing the code, visualisations and results. 

There are 3 aditional data sets/csv files. The SO_2013.csv file is the data from the Stackoverflow questionary conducted in 2013.
The files SO_2018-1.csv and SO_2018-2.csv are data from the Stackoverflow questionary conducted in 2018. 
I had to split the 2018 questionary data into two files, to be able to upload them to github (file size limitations). 
The two files are merged again the python workbook. 

Note that the questionary structure between 2013 and 2018 has changed a lot. 
Cleaning the data and making the featues comparible was quite challenging, but even so some featues had to be dropped to avoid potential mistakes in the interpretation of the results.

Original data can be found here: https://insights.stackoverflow.com/survey


## Results <a name="Results"></a>

The IT industry had gone through some interesting changes in the past 5-6 years.
Plots which show the changes are not fully comparible, but some conclusions can still be made
The Bar Plots which compare the share of programming languages used by the commmunity, show how the popularity of Python continues to increae, now beating C# and PHP in a relative number of users.


