# Matplotlib_Challenge
Matplotlib Challenge - Pymaceuticals

# Matplotlib - The Power of Plots

## Disclaimer
Some of the code has been discussed with the instruction team and peers considering the challenges and to find best solution to the problem.
General websites have been referred for code accuracy including matplotlib.org, geekforgeeks.com, stackoverflow.com

## Background

What good is data without a good plot to tell the story?

This activity is to utilize Python Matplotlib and apply it to a real-world situation and dataset:

Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


## Please use below URL in order to view jupyter notebook output as it may not be displayed correctly within github.
https://nbviewer.jupyter.org/github/Rupalis123/Matplotlib_Challenge/blob/main/Pymaceuticals/pymaceuticals_starter_v1.ipynb

## Please refer MatplotlibChallengeObservations.pdf for detail observations.


## Observations

Main purpose of this analysis was to show how 4 selected treatments compare.

* Capomulin and Ramicane reduces the size of tumors better than other drug regimens. 

* The correlation between mouse weight and average tumor volume is 0.84. It indicates a strong positive correlation, when the mouse weight increases the average tumor volume  also increases.

* The regression analysis demonstrates, how much the average tumor volume will change when weight of mice changes. The R-squared value is 0.70, which means 70% the model fit the data so it is a good fit for prediction.

* One potential outlier has been observed within the Infubinol regimen. Most mice showed tumor volume increase, however one mouse has shown a reduction in tumor growth.

## Instructions

Your tasks are to do the following:

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

  * **NOTE:** These plots should look identical.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

  * **NOTE:** These plots should look identical.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

  **Hint**: All four box plots should be within the same figure. Use this [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.

Here are some final considerations:

* You must use proper labeling of your plots, to include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* See the [starter workbook](Pymaceuticals/pymaceuticals_starter.ipynb) for help on what modules to import and expected format of the notebook.




### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
