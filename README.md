# Matplotlib - The Power of Plots

If you would like to see my finding, please scroll down to the findings section.

## Background

What good is data without a good plot to tell the story?
In this assignment, I took on the role of of a data scientist, working for Pymaceuticals, Inc. a burgeoning pharmaceutical company.
The company began screening for potential treatments for squamous cell carcinoma(SCC), a commonly occurring form of skin cancer.
I've been given to the complete data from their most recent study covering 250 mie idetntifed with SCC tumor growth.
Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Capomulin versus the other treatment reignemnts.
I have asked to generall all of the tables and figures needed for the technical report of the study.
The executive team also hased for a top-level summary of the study results.

## Reporting Steps

### Summary Statistics Table

- I created a table including the following:
  - Mean
  - Median
  - Variance
  - Standard Deviation
  - SEM of the tumor volume of each drug regimen

## Findings

These are my three inferences or observations of the data:

1.  There is almost a near positive correlation between the mouse's weight and the tumor volume. In fact with a correlation coefficient at 0.95, it is almost certain that these two are positively correlated.
2.  On mouse ID s185, there was a significant decrease in the tumor volume over the time period. The tumor volume on this mouse went from 45 cubic millimeters to less than 25 cubic millimeters, showing real promise for this drug.
3.  With the exception of 1 mouse on Infubinol, all four reigmens showed consistent results regarding the tumor volume of the mice at the end. Looking at the box and whisker plot, Capomulin and Ramicane seemed to be the most promising of results with the tumor volumes taken at maximum time point having a median of less than 40 cubic millimeters. Infubinol and Ceftamin still had median tumor volumes closer to 60 cubic millimeters.
