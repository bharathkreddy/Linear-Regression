# ML BOOTCAMP 
# Week 4 LINEAR REGRESSION - THEORY

[This notebook]() is a step-by-step intro to get an intution around Linear Regression and steps to build a regression model.
I explain how to interpreset coefficient of regression and metrics like R2 and RMSE intuitively and how to expand the model by adding complexities.




[This notebook]() is a step-by-step intro to get an intution around Linear Regression and steps to build a regression model.
I explain how to interpreset coefficient of regression and metrics like R2 and RMSE intuitively and how to expand the model by adding complexities.

## Details about data source.
### California Housing

This dataset is a modified version of the California Housing dataset available from [Luís Torgo's page](http://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html) (University of Porto). Luís Torgo obtained it from the StatLib repository (which is closed now). The dataset may also be downloaded from StatLib mirrors.

This dataset appeared in a 1997 paper titled *Sparse Spatial Autoregressions* by Pace, R. Kelley and Ronald Barry, published in the *Statistics and Probability Letters* journal. They built it using the 1990 California census data. It contains one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

## Tweaks
The dataset in this directory is almost identical to the original, with two differences:

* 207 values were randomly removed from the `total_bedrooms` column, so we can discuss what to do with missing data.
* An additional categorical attribute called `ocean_proximity` was added, indicating (very roughly) whether each block group is near the ocean, near the Bay area, inland or on an island. This allows discussing what to do with categorical data.

Note that the block groups are called "districts" in the Jupyter notebooks, simply because in some contexts the name "block group" was confusing.


