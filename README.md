# Civic data analyses

## Business Case

We're going to look at the initiative to move the needle on one of two separate issues: high school education outcomes, or drug abuse in the community.

we have two datasets on hand: one on SAT scores by state, and one on drug use by age. We're going to start exploring these to look for useful patterns and possible hypotheses!

--- 

## Overview

This project is focused on exploratory data analysis, aka "EDA". EDA is an essential part of the data science analysis pipeline. Failure to perform EDA before modeling is almost guaranteed to lead to bad models and faulty conclusions. 

We are going to spend time time trying to understand the data, through both summary statistics and visualization. By the end, we will want to be familiar enough with the datasets to think of testable hypotheses that could point in specific policy directions.

We will be doing the following things:

- For statistics questions, Python code -- using pandas, numpy, scipy, and/or other libraries -- 
- For plotting questions, labeled seaborn or matplotlib plots displayed within your notebook, with Markdown interpreting the results

---

## Dataset Description

---

drug-use-by-age.csv

- 17 rows, 28 columns (imported)
- n is sample size (number of people in age group)

sat_scores.csv

- 53 rows, 4 columns
- Rate is the participation rate, 0-100%

---

## Objectives

1. Analyze diverse datasets & explicitly state your assumptions.
2. Form hypotheses and justify them with solid statistical testing in NumPy. 
3. Visualize and interpret your plots using Matplotlib and Seaborn. 

## Useful Resources

-A [cheatsheet](https://chrisalbon.com/python/pandas_dataframe_descriptive_stats.html) of descriptive statistics methods in Pandas.

- The [seaborn example gallery](http://seaborn.pydata.org/examples/) may help you find the right code, and decide what you want to do in the first place.

- https://python-graph-gallery.com/

- https://stanford.edu/~mwaskom/software/seaborn/generated/seaborn.distplot.html#seaborn.distplot

- http://pandas.pydata.org/pandas-docs/stable/visualization.html

- http://pandas.pydata.org/pandas-docs/stable/indexing.html

- http://docs.scipy.org/doc/numpy-dev/reference/generated/numpy.percentile.html

- http://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.percentileofscore.html

