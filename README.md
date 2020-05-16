# House-Price-Advance-Regression
Kaggle Competition "Advance House Prices Regression" Kaggle Rank top 2%

## Summary:
Suppose you want to buy a new house, what are the factors that you will consider. My top factors would be the Number of Rooms, Number of Bathrooms, Street Access, whether it has a Garage. But if the house has a each of these features, it would be quite expensive.

So eventually the house you buy has to be a balance between the features you want, and the price you are willing to pay. The dataset we have explains the price of 1500 such house with all the features they have, so that you can analyze the features and their effect they have on the price.

For a buyer you can estimate the price you should be paying for a property, and for a seller you can estimate a quoting price for a property.

## Objective:
To predict house prices based on 79 explanatory variables.

## DataSet:
The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset.

## Procedure:
1. Data exploration for missing values, outliers
2. A thorough data cleaning exercise based on business understanding
3. Feature engineer to create intuitive new features
4. One hot encoding to convert categorical features to encoded columns containing zeroes and one's
5. Training test split
6. Trying basic models- first pass
7. 37 skewed numerical features to Box Cox transform, to improve accuracy
8. Testing a custom stacked regression model, which aggregates the prediction from various models


### The model shows that the features which play an important role in deciding the price of a property

The most important features are
1. The above ground living area of the property
2. The surface area of the basement
3. Area of the entire lot
4. Surface area of the first floor
5. Basement area
6. Garage area

