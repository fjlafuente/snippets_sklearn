# snippets_sklearn

## Preparing data
````python

#Linear Regression
from sklearn.linear_model import LinealRegression
#Create an instance of the model
reg = LinearRegression()
#Fit the regressor
reg.fit(X,y)
#Do predictions
reg.predict([[2540][3500],[4000]])
