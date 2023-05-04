# DataMining2_FinalProject
My task in this project was to predict and classify donations for Multiple Sclerosis (MS) amounts based on various variables. I had to use a multivariable regression model, a neural network, and an ensemble model with a neural network combined with a decision tree classifier. The data was loaded through Microsoft SQL Server and imported into R. Python was used to clean the initial datasets from special characters which were making the importing process difficult.

## Steps
1. Import top 50000 rows from the BikeDonations and 87 rows from BikeEvents
2. Merge them by 'EventID'
3. Remove NA variables
4. Split categorical variables into binary dummy variables
5. Normalize the numeric columns of the dataset
6. Build a train/test split of the data
7. Feed data into the neural network and multivariable regression
8. Compare results, extract significant variables and re-run the two predictive models
9. Prepare a new neural network based on several handpicked variables and predict the outcome
10. Using the predicted variables, not the actual variables, first classify them into two bins [Low Donations, High Donations]
11. Send the new predicted values into the decision tree
12. Calculate the confusion matrix, ROC curve, and Area under ROC for model significance
