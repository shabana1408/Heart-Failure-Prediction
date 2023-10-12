![heartfailure](https://github.com/shabana1408/Project-2/assets/138613948/a7f62f76-b6e2-4d9f-bde3-b64b2098a752)

# Heart Failure Prediction
### Early detection of heart failure in patients

**Author**: Shabana Patel 

### Business problem

The purpose of this project is to improve early detection of heart failure in patients. This can lead to better patient outcomes and lower healthcare costs.

### Stakeholders

Healthcare providers, healthcare funders, policyholders and patients.

### Data

[Original source](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

The data represents 918 observations, 11 features and 1 target variable.

### Methods
To prepare the data, the data was inspected and cleaned and the following processes were performed:

#### Exploratory Data Analysis
EDA is performed to understand the main characteristics, patterns and relationships within a datset. 

#### Feature by feature inspection
Individual features in the dataset were considered to understand their distributions, patterns and significance in relation to the target variable. 

#### Feature engineering
This is the process of selecting, creating, or transforming data attributes to enhance the performance of machine learning models.

### Insights
The data analysis revealed that certain patient demographics are strong predictors for heart failure.

#### Patients by gender
![viz1_patientsbygender](https://github.com/shabana1408/Project-2/assets/138613948/635bad41-55c9-4977-b9d1-d13332f43472)

- 90% of patients presenting with heart disease are male, while 10% are female.
- However, 65% of normal patients are male, while 35% are female.

#### Patients by age band
![viz2_patientsbyageband](https://github.com/shabana1408/Project-2/assets/138613948/35531f4f-412b-41ff-8b76-be3e928b2760)

- 78% of patients presenting with heart disease were 50 years and old compared to the 56% of normal patients who were 50 years and older.
- The average age of a heart failure patient is five years older than a normal patient at 55.9 years. 

### Model

Models considered:
- Random Forest Classifier Model
- Gradient Boosting Classifier Model
- Support Vector Machine Model


The final Machine Learning model chosen is a Random Forest Classifier Model. Based on the testing dataset:
- The model has high predictive accuracy indicating that it classifies both Heart failure and Normal cases 89% of the time.
- The model demonstrates high precision for predicting Heart failure, i.e. when the model predicts Heart failure, it is correct 92% of the time.
- The model has good recall for Heart failure, i.e. it correctly identifies 89% of actual Heart failure cases.

### Solving the business problem

The model may be deployed as an early warning system within the healthcare provider or healthcare funders system, such that when a patients data is entered, the model can assess their risk of heart failure. Healthcare providers can also be prompted to take preventative measures or schedule additional tests for high-risk individuals.

### Recommendations for stakeholders

Stakeholders can incorporate the model's risk assessment tool into routine patient visits to help identify high-risk patients early. This will allow for timely interventions and personalised care plans.

Stakeholders can educate patients on the importance of adopting and maintaining a heart-healthy lifestyle by raising awareness about heart failure risk factors and prevention strategies. 

### Next steps

Explore ways to collect more patient data to produce a more generalised model.

### Additional information
Contact:

Shabana Patel
shabana.patel@momentum.co.za