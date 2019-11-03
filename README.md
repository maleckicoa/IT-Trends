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

After cleaning the 2013 data contains around 9K observations, and 2018 data contains 90K and 11K (for the 1st and 2nd part of the work respectively) observations.

Original data can be found here: https://insights.stackoverflow.com/survey


## Results <a name="Results"></a>

The IT industry had gone through some interesting changes in the past 5-6 years.

Plots which show the changes are not fully comparible, but conclusions can still be made.
The Bar Plots which compare the share of programming languages used by the commmunity, show how the popularity of Python continues to increase, now beating C# and PHP in the relative number of users. At the same time, objective-C looses its share to R and Ruby which are now ranked before it.

Bar Plots which compare the relative share of different Job positions in the IT community, show how the demand for Database Administrators has increased lately, and the same applies to System Administrators.

Finally, in the 2nd part of the work I made some effort to predict in which Salary Bin a professional might expect to fall in, based on his questionary data of 2018. The model used was Random Forrest Classifier. Although the prediction results leave a lot of room for improvement (F-score ~ 0.51) the significance of features which (according to the model) were most important, shows interesting findings. 
It appears that experience is the most important factor leading to high salary (Age and Years of Coding). Also, there are high differences in salary depending on the Operative System in which the develloper is working, with BSD/Unix developpers earning significanlty more than other.

## Licensing <a name="Licensing"></a>

All credits for the datasets go to StackOverflow. 
The data is generally free to use, all licencing details can be found here:
https://www.kaggle.com/stackoverflow/stack-overflow-2018-developer-survey
