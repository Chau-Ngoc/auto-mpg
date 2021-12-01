# Welcome to this notebook
In this notebook we will analyze the "auto-mpg" dataset collected from the [UCI machine learning repository](https://archive.ics.uci.edu/ml/index.php) and create two regrssion models to predict a vehicle's fuel efficiency.

**Note**: due to github's policy, you won't be able to see the plotly's histogram if you open the notebook on github. If you wish to view the completed notebook, go to [nbviewer](https://nbviewer.org/github/Chau-Ngoc/auto-mpg/blob/main/auto_mpg_prediction.ipynb)

The descriptions for each column in the dataset are as follows:
1. mpg: continuous
2. cylinders: multi-valued discrete
3. displacement: continuous
4. horsepower: continuous
5. weight: continuous
6. acceleration: continuous
7. model year: multi-valued discrete
8. origin: multi-valued discrete
9. car name: string (unique for each instance)

The two models used in this notebook are Linear Regression model and Polynomial Regression model. We will compare how each model perform base on R_squared and RMSE score.

Then we will use the better model to predict a new make-up data.

Enjoy!
