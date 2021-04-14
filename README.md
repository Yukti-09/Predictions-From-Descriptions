# Predictions-From-Descriptions
Prediction of the primary product category from its description.<br>

## Cleaning it up
First, the primary product category is found from the product category tree. <br>
Following which any extra characters such as '.' are removed. Numbers are also removed.

## Throwing problematic data out
According to the plot, the data is highly imbalanced. <br>
The top 5 categories are considered for prediction. <br>
The rest of the categories are dropped for this analysis.

## Making the machine learn it
The dataset is split. 80% of the dataset is used for training and 20% is used for testing. <br>
Multinomial Naive Bayes and Linear Support Vector Machines are used. <br>
The accuracy obtained for them is 99.27% and 99.84% respectively. <br>

### Greedy for more accuracy? 
Use LSTMs and GRUs. <br>
Make use of more features.
