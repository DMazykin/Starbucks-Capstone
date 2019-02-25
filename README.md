# Udacity Starbucks Capstone Challenge 
by Denis Mazykin

## Motivation:

This challenge is one of the final projects for Udacity Data Science Nanodegree course.
For this project, we have datasets from Starbucks which contain simulated data that mimics customer behaviour on the Starbucks rewards mobile app. 

The reason why companies use different offers or discounts campaigns is to stimulate customers to come more often and spend more. This ultimately helps to increase the revenue and profit for the company. In this project I'll try to link the response to the offers with the overall customer behaviour. This can help us to understand the structure of the customer and develop strategies for different groups.

The end goal is to find some segments of the current customers depending on their behaviour and figure out which segment would be the most interesting for a further advertisement campaign and where we can change the frequency of offers.

## Results:

I was managed to find 5 different groups with unsupervised machine learning algorithm (K-Means). With this information, a company can implement some different marketing campaigns for each group depending on the general strategy.

For this project, we have data only for the one-month period, but it would be interesting to analyze a longer period, like several months or even years. Then we can see the structure (clusters) changes over time and could also estimate the impact of changing offer’s parameters like frequency of campaign, offers’ difficulty, duration and reward.

More details in [my blog post](https://medium.com/@denmaz/starbucks-customers-2579d5e57944)


## Library used in analysis:
- python 3.6
- numpy
- json
- locale
- pandas
- warnings
- scikit-learn
- math
- matplotlib
- seaborn


## Files in the repository:

- `Readme.md` - this readme file
- `Starbucks_Capstone_notebook.ipynb` - Jupyter notebook with a code for analysis and data visualization
- `data/` - folder contains the data for analysis
- `Plots/` - folder contains the plots for blog post

## References:
- Scikit-learn: https://scikit-learn.org/stable/modules/classes.html
- StackOverflow: https://stackoverflow.com
- Seaborn: https://seaborn.pydata.org/api.html
- https://medium.com/jbennetcodes/dealing-with-datetimes-like-a-pro-in-pandas-b80d3d808a7f
- https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/
  