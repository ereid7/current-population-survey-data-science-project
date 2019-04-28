# Current-Population-Survey-Data-Science-Project
An exploratory data science project using the 2016 Current Population Survey. This project is for the MSCS-335 Machine Learning course at University of Wisconsin - Stout.

Please refer to the [CPS Dataset Description](DatasetDescription/CPSDatasetDescription.pdf) for a description of each variable and their valid entries

The Current Population Survey is one of the oldest, largest, and most recognized surveys in the United States. This survey provides information about individuals in society such as work, earnings, and our education. The CPS is used to collect data for a variety of other studies that keep the nation informed of the economic and social well-being of its people. This survey is taken monthly, however the Census Bureau website does not provide the raw data of survey responses from individuals unless you have the access rights. However, a few months of the survey have been published online. The August 2016 CPS dataset can be found in a raw .CSV format on Kaggle.com via the following link:

https://www.kaggle.com/census/current-population-survey

My goal was to create a dataset that is much like the UCI Adult dataset (from 1995):

http://mlr.cs.umass.edu/ml/datasets/Adult

The 2016 CPS dataset has many columns and many incomplete survey answers, so I edited the to capture the most relevant data. It is important to note that I have stripped the data of any multiple-job holding individuals, so the data only reflects individuals with a single occupation. This updated version of the 2016 CPS dataset is very similar to the UCI adult dataset with some added columns.

The Current Population Survey (CPS) is administered, processed, researched and disseminated by the U.S. Census Bureau on behalf of the Bureau of Labor Statistics (BLS).
