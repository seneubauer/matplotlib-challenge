# matplotlib-challenge

## Problem
In this assignment, we were asked to present a variety of analyses on a given dataset. The dataset in question provided us with data on treatment regimens for tumor development in mice.

## Goal
### Tasks (copied from assignment)
* Prepare the data.
* Generate summary statistics.
* Create bar charts and pie charts.
* Calculate quartiles, find outliers, and create a box plot.
* Create a line plot and a scatter plot.
* Calculate correlation and regression.
* Submit your final analysis.

## Setup
In order to perform the desired analyses, I had to merge the two provided CSVs into one DataFrame then use this DataFrame as the root data source. In different sections I performed various methods on this data source to create an appropriate allotment of data. These methods included df.loc, df.groupby, pd.merge, and df.value_counts to name a few. I decided to employ an 'input' to provide a value for the requested line plot.

## Execution Notes
This script takes some time to execute, and is further slowed down by the aforementioned 'input' function. But I set it up so the results are obvious, labeled, and sectioned.

## Limitations
A source of potential inefficiency is the cell where I check for and remove duplicated Timepoint data. Perhaps there is a better process for achieving the same result using native Pandas methods but I could not find one in the time provided. In lieu of that I returned to my roots and wrote out the for loop and its accompanying logic.