# Cardiovascular Predictor Models
The focus of my cardiovascular predictor models are to calculate the likelihood of getting heart disease.

## Library and Data Input 
An input of packages and specific functions that may be useful to our model.

### Features and Target
A list of features and the target from the dataset





## Data Cleaning
After being completely converted to floats and checked for null values, the column, 'id' was dropped due to lack of value for our model. All heirarchical columns were assigned unique columns.





## Model Creation & Training


### Establish Feature and Target
Features and the target were set to variables. 


### Multicolinearity Check
Correlations of unique features above 0.7 need to be dealt with to minimize colinearity.

### Test-Train Split
80% of the data was used for training. 20% of the data was use for testing.

### Scaling & SVC
Scalers and Support Vector Classification to further prepare and analyze our data.

### Logistic Regression
Logistic Regression fitting

#### Test-Train Correctness
Both were 72% correct.

#### Logistic Regression's Feature Importance
Identification of the most impactful features of the logistic regression model. 

### Accuracy & Classification Report
Accuracy, precision, recall, f1-score, support.

### Confusion Matrix
False positives, false negatives, true positives, and true negatives

### Decision Tree
Tree-like decision model.
 
### Random Forest
10 decision trees with variation.

#### Random Forest's Feature Importance
Identification of the most impactful features of the random forest model. 






## Model Boosting


### GridSearchCV
Fine tunes parameters.

### Gradient Boost
This ensemble method will boost model accuracy to 74%.

### XG Boost
Extreme Gradient Boost kept model accuracy roughly at 74%.





## Conclusion
We used several algorithms and visualizations to maximize our model's accuracy. Ultimately, we achieved an accuracy of about 74% which is great for our dataset. The CD Predictor models were a success.