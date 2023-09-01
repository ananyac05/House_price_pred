## House_price_pred
We all have experienced a time when we have to look up for a new house to buy. But then the journey begins with a lot of frauds, negotiating deals, researching the local areas and so on.

## House Price Prediction using Machine Learning
So to deal with this kind of issues we built a MACHINE LEARNING Based model, trained on the House Price Prediction Dataset. 

## Importing Libraries and Dataset
- Pandas – To load the Dataframe
- Matplotlib – To visualize the data features i.e. barplot
- Seaborn – To see the correlation between features using heatmap

## Data Preprocessing
we categorize the features depending on their datatype (int, float, object) and then calculate the number of them. 

## Exploratory Data Analysis
We did deep analysis of data so as to discover different patterns and spot anomalies.

## Data Cleaning
cleaned our dataset to improvise the data or remove incorrect, corrupted or irrelevant data.
- As Id Column will not be participating in any prediction. So we can Drop it.
- Replacing SalePrice empty values with their mean values to make the data distribution symmetric.
- Drop records with null values (as the empty records are very less).

## OneHotEncoder – For Label categorical features
One hot Encoding is the best way to convert categorical data into binary vectors. This maps the values to integer values. By using OneHotEncoder, we can easily convert object data into int.

## Models 
- Random Forest Regressor
- Linear Regressor

## Conclusion
Clearly, Linear Regression model is giving better accuracy as the mean absolute error is the least among all the other regressor models i.e. 0.18 approx.
.
