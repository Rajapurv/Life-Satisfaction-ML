# Life-Satisfaction-ML
This is a simple ml project which predicts the life satisfaction of country based on there GDP per capita
You can also use k-nearest neighbors regression algorithm instead of linear regression
To achiive it Follow below :
Replace these lines
 * from sklearn.linear_model import LinearRegression 
 * model = LinearRegression()
with these
 * from sklearn.neighbors import KNeighborsRegressor
 * model = KNeighborsRegressor(n_neighbors=3)
here n_neighbors will take the average of 3 closest GDP
 For example if you want to know the life satisfaction of israil with gdp 50000,
then this model will take the closet 3 number to 50000 in GDP and take there life satisfaction numbers and calculate the average out of it.
Both linear Regression and k-nearest neighbor gives same results or closet result.

Thanks for visiting my Git Hub
Please follow me on linkedin for more detail
https://www.linkedin.com/in/apoorv-raj-990a91153/
