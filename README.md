# Machine_Learning

1. Do these factors correlate?

I wanted to check if "Years in education" and "Homicide rate" affect one another. The data is from here : https://github.com/ageron/handson-ml/blob/master/datasets/lifesat/oecd_bli_2015.csv

And so, I did the following :

- Chosen a regression model
- Split the dataset into two subsets: training dataset and testing dataset by considering stratification/structure of data (stratified sample). Repeat this operation 3 times to get 3 different splits of the above dataset into (training_data, testing_data).
- Trained 3 times the chosen regression model with the above 3 training datasets by removing the non-representative instances from each training dataset.
- Evaluated the model performance measures for each of 3 training datasets.
- Re-evaluated the model performance using cross-validation for each training dataset.
- Tested the model with the 3 test datasets obtained above.
- Printed out performance differences between the 3 datasets and choose the better one.
