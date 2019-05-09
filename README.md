# Current-Population-Survey-Data-Science-Project
An exploratory data science project using the 2016 Current Population Survey. This project is for the MSCS-335 Machine Learning course at University of Wisconsin - Stout.

Please refer to the [CPS Dataset Description](DatasetDescription/DATA_DESCRIPTION.md) for a description of each column and their valid entries

The Current Population Survey is one of the oldest, largest, and most recognized surveys in the United States. This survey provides information about individuals in society such as work, earnings, and our education. The CPS is used to collect data for a variety of other studies that keep the nation informed of the economic and social well-being of its people. The August 2016 CPS dataset can be found in a raw .CSV format on Kaggle.com via the following link:

https://www.kaggle.com/census/current-population-survey
Kaggle does not provide an accurate data description for the data (but somebody found the correct dict in the comments), so find the real data dict for the original dataset [here](https://thedataweb.rm.census.gov/pub/cps/basic/201501-/January_2015_Record_Layout.txt)

My goal was to create a dataset that is much like the UCI Adult dataset (from 1995):

http://mlr.cs.umass.edu/ml/datasets/Adult

The 2016 CPS dataset has many columns and many incomplete survey answers, so I edited the to capture the most relevant data. It is important to note that I have stripped the data of any multiple-job holding individuals, so the data only reflects individuals with a single occupation. This updated version of the 2016 CPS dataset is very similar to the UCI adult dataset with some added columns.

The two main response variables that are used in the classification methods are 'is married' and 'family income over $50,000'. One of the most successful methods was Random Forest Decision Tree Classification.

Determined if an individual is married with 83% accuracy using the following predictors:
- age, hours worked weekly, education, number of people in household, number of children under 18, family income

Determined if an individual's family income is greater than $50,000 with 74% accuracy using the following predictors:
- age, hours worked weekly, education, number of people in household, number of children under 18, marital status

The Current Population Survey (CPS) is administered, processed, researched and disseminated by the U.S. Census Bureau on behalf of the Bureau of Labor Statistics (BLS).
