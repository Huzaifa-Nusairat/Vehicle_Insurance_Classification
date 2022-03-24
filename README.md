
-   ## Vehicle_Insurance_Classification
![alt text](https://github.com/Huzaifa-Nusairat/Vehicle_Insurance_Classification/blob/master/Images/V-Insurance.jpg?raw=true)
prepared by:Huzaifa Nusairat

-   ## problem overview

- Insurance companies try to improve customer service, fraud detection, and operational efficiency by providing Health Insurance to their customers.
That insurance policy is an arrangement by which a company undertakes to provide a guarantee of compensation for specified loss, damage, illness, or death in return for the payment of a specified premium.
On The other hand the customer has to pay regularly to an insurance company for this guarantee.


- The objective of the project is:
 Build a model to predict whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company.

-   ## Solution process

### Discuss about The Data:

- I got the data set from kaggle competition:
https://www.kaggle.com/c/vehicle-insurance-classification-tah/data?select=train_set.csv

- The data set has (12) Columns & (305723) Rows:

 id: customer ID.
 Gender: Male or Female.
 Age: from (20)years old to (85)years old.
 Driving_License: (1) have a Driving License
(0) does not have Driving License.
 Region_Code: Code number for the place he/she lives in.
 Previously_Insured: (1)Yes or (0)No.
 Vehicle_Age: '<1 Year', '1-2 Year', '>2 Year'.
 Vehicle_Damage: if The Vehicle damage(Yes) or Not (No).
 Annual_Premium: is a sum of money that the customer needs to pay regularly to an insurance company for this guarantee range from (2.63k) to (540k).
 Policy_Sales_Channel: is the sales agency id its range from (1) to (163).
 Vintage: is the days of health insured till now for the customer its range from (10) to (299).
 Response: Whether the policyholders (customers) from past year will also be interested in Vehicle Insurance provided by the company (1) or not(0)

### Analytical approach:
- The Work Flow of this project:
![alt text](https://github.com/Huzaifa-Nusairat/Vehicle_Insurance_Classification/blob/master/Images/VIC_Flow_Chart.jpeg?raw=true)

### Analyze The Data :

- At first The Data does not have missing values, When I did Univariate analysis There was one Feature with an outliers which is 'Annual_Primum', I got rid of them using IQR (Interquartile Range), Then I found that The data has Imbalanced features which are 'Driving_License' and The Target 'Response', I resampled The Target using an OverSampling technique (SMOTE).

##### Nominal Features:
![alt text](https://github.com/Huzaifa-Nusairat/Vehicle_Insurance_Classification/blob/master/Images/Categorical_features.jpeg?raw=true)

##### Continuous Features:
![alt text](https://github.com/Huzaifa-Nusairat/Vehicle_Insurance_Classification/blob/master/Images/Numerical_Features.jpeg?raw=true)

##### Target Feature:
![alt text](https://github.com/Huzaifa-Nusairat/Vehicle_Insurance_Classification/blob/master/Images/Target_feature.jpeg?raw=true)

- ![alt text](?raw=true)
- for Bivariate Analysis I Observed that
### Model validation:

1- how you validate the model!

2- how you can check the performance of the model !

3- how it is predicting !

-   ## Models comparison

How each model is performing on training data** **and testing data.

-   ## key finding

It is the most important factor that influence through the problem and
number them in order .

-   ## preventive measures

You can discuss the preventive measure and what kind of preventive areas
you can take to avoid the problem or reduce the disease or fraud
detection.

-   ## Recommendation

Give recommendation upon your model prediction and explain your
recommendations.

-   ## Potential benefits

What kind of potential benefits are given (The sense of the business) it
should be at least three.