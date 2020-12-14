# GBT_RF_Diamonds
In this exercise, I used the diamonds.csv dataset from Kaggle to build tree based models that attempt to predict diamond price using PySpark. If you haven't already, please see my other repository where I used linear regression to accomplish the same task. Overall, I was able to reduce the MSE from 1307177 to 437,555 using a GBT and random forest regressor.

The diamonds.csv data set contains 10 columns:

- carat: Carat weight of the diamond
- cut: Describes cut quality of the diamond. Quality in increasing order Fair, Good, Very Good, Premium, Ideal
- color: Color of the diamond, with D being the best and J the worst
- clarity: How obvious inclusions are within the diamond:(in order from best to worst, FL = flawless, I3= level 3 inclusions) FL,IF, VVS1, etc. See this web site for an exhaustive ranking of clarity. The web site has a nice sliding scale you can drag to see the relationship between clarity grades.
- depth: depth % - The height of a diamond, measured from the culet to the table, divided by its average girdle diameter
- table: table% - The width of the diamond's table expressed as a percentage of its average diameter
- price: The price of the diamond
- x: Length (mm)
- y: Width (mm)
- z: Height (mm)

