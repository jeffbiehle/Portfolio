## Walmart Store Comparison Analysis
As part of a Kaggle competition from 5 years ago, Kaggle was able to obtain very detailed store data from Walmart on 45 Walmart stores across the US. The data includes weekly revenue by department for each store in the data set, as well as supplemental data such as type of store (assumed to be Walmart Supercenter, standard Walmart, and Walmart Neighborhood), size of store (in square feet); weekly stats by store on average temperature, unemployment rate, CPI; and info on holiday weekends.

My experiment will be focused on running a 6-week TV ad campaign in the areas of the stores that had the lowest revenue per square foot in 2012. My assumption is that each store in the dataset is in a different city so that results won't be biased. My hypothesis is that the revenue for those stores that were targets of the TV campaigns will see greater increases (measured by percentage of revenue) than those that did not receive the TV ads.

There are three files that comprise the data set:
- stores.csv: This file is a small file that lists each store along with category (A, B, or C) and size in sq. ft.
- train.csv: This file provides weekly sales data per store per department
- features.csv: This file lists the extraneous variables for each store by week (temp, unemployment, CPI, etc.)

For this experiment I will only be using the stores.csv and train.csv files. Future experiments could involve using the features.csv file as well.
