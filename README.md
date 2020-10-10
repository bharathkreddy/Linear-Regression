# ML BOOTCAMP [visit website to get full course](www.bharathkreddy.com)
# Week 4 LINEAR REGRESSION - THEORY

> [Visual explanation of OLS technique](https://bharathkreddy.github.io/Linear-Regression/)

[This notebook](https://github.com/bharathkreddy/Linear-Regression/blob/master/BRK.ipynb) is a step-by-step intro to get an intution around Linear Regression and steps to build a regression model. I explain the below concept using data on money spent on advertising on 3 channels - TV, Radio and Newspaper and use these to predict sales of a product.
 1. Linear Regression Theory,
 2. Theory of behind curve fitting 
 3. Interpretation of coefficients of regression and intercept
 4. How to build a model using more features
 5. Adding interaction features.
 6. Measuring how good our model predictions are using RMSe and R2 statistic.

# Week 5 LINEAR REGRESSION - PRACTICE
[This notebook](https://github.com/bharathkreddy/Linear-Regression/blob/master/California%20prices.ipynb) is a step-by-step intro to get an intution around Linear Regression and steps to build a regression model.Dataset used is California Housing dataset. I explain the below concepts.
1. How to frame a problem statement.
2. Exploratory Data Analysis (univariate and bi-variate) 
3. Missing value identification and treatment
4. Outlier detection and treatment
5. Preparing our data for ML algorithm by using automated processing pipelines.

These form the building blocks for any Machine Learning and can be reused.
Finally we predict housing prices by implimenting Linear Regression model we get a model score of 68%. We use statistics explained in week 4 (R2 , Fscore and RMSE to measure our algorithm performance)


## Details about data source.
### California Housing

This dataset is a modified version of the California Housing dataset available from [Luís Torgo's page](http://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html) (University of Porto). Luís Torgo obtained it from the StatLib repository (which is closed now). The dataset may also be downloaded from StatLib mirrors.

This dataset appeared in a 1997 paper titled *Sparse Spatial Autoregressions* by Pace, R. Kelley and Ronald Barry, published in the *Statistics and Probability Letters* journal. They built it using the 1990 California census data. It contains one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

## Tweaks
The dataset in this directory is almost identical to the original, with two differences:

* 207 values were randomly removed from the `total_bedrooms` column, so we can discuss what to do with missing data.
* An additional categorical attribute called `ocean_proximity` was added, indicating (very roughly) whether each block group is near the ocean, near the Bay area, inland or on an island. This allows discussing what to do with categorical data.

Note that the block groups are called "districts" in the Jupyter notebooks, simply because in some contexts the name "block group" was confusing.


