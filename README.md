# Boston Housing Dataset
![Boston Housing Authority - Boston Housing Authority](https://th.bing.com/th/id/OIP.8dyvyYEjoyuVgd7Gse4V3gHaGj?pid=ImgDet&rs=1)
## Objective
- To perform neccessary exploratory data analysis to know some interesting fact about Boston neighbourhoods out of this dataset.
- Create a model using the multiple linear regression to predict the price when user inputs the variables.
##  About the dataset
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA.  It was originally from UCI Machine Learning Repository but now it has been deleted. This dataset consist of  506 samples and 14 variables. The following describes the dataset columns:
- CRIM - per capita crime rate by town
- ZN - proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS - proportion of non-retail business acres per town.
- CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- NOX - nitric oxides concentration (parts per 10 million)
- RM - average number of rooms per dwelling
- AGE - proportion of owner-occupied units built prior to 1940
- DIS - weighted distances to five Boston employment centres
- RAD - index of accessibility to radial highways
- TAX - full-value property-tax rate per 10,000
- PTRATIO - pupil-teacher ratio by town
- B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT - % lower status of the population
- MEDV - Median value of owner-occupied homes in $1000's


#  Insights
- Most of the Boston's neighbourhood tract does not bounds the river. As the numbers are low, we can expect a huge market prices for the neighbourhood near river as supply is too low. According to the law of supply, lesser the supply of a particular neighbourhood the more the price is.

- More number of neighbourhoods are near Charles river, which has price of houses more than 50000 dollars. The higher price is due to fewer number of neighbourhood around the river.

- It is  surprisingly visible that neighbourhood with higher accessibility to highways has lower value compared to the one's with less accessible. By this we can find that people prefer more secluded way of living in Boston.

- Value of the neighbourhoods does not have a strong corelation between them. I hope these people are not looking to stay near the employent center. Usually, other part of the world, the value of houses rises when they are close to employment center. Although some of the neighbourhoods near five employment centers are costly. Mostly, we can find the Boston neighbourhoods do not demand their houses near their employment center.

- The data prooved that number of crimes committed for each person in town is very low. As the data comes from the record of 1970, there was decrimination of white people and black people. Even at that time, neighbourhood filled with black people had few crime rate in Boston. 
- The neighbourhood with people who are rich live in a area with peaceful atmosphere. Whereas, the neighbourhood with less income people live in a area where the pollutants are high. It shows some degree of slump area over the region of Boston.
- Most of the people who are poor stays at old homes only. There are neighbourhood in which homes have value more than 15000 dollar. We can tell that few of the poor community can become richer by selling their homes. I am not sure why are they hesitant.


##  Modelling
Using this dataset, multiple linear regression model was performed. Initially before performing the modelling, null values were checked but not found any. As the columns were already numerical in nature, there was no encoding required to be performed. The data was finally spllitted to create the testing and training data. From  sklearn linear model the linearRegression was performed and then it was fited to the training data. Predictions of both training and testing data was carried out. Training data had good accracy compared to the testing data as the R-Squared value was closer to 1.

/<p align="center"> ![Boston Housing Authority - Boston Housing Authority](https://th.bing.com/th/id/OIP.ffcaRISgEAiLqJlbUzPFmwHaFj?pid=ImgDet&rs=1)

<p>
