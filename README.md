## **Navigation System To Avoid Accident Prone Areas Using Machine Learning Techniques**

The main objective of this project is to create an advanced navigation system that utilizes machine learning techniques to help users avoid accident-prone areas. The research data used for this project consists of daily accident reports obtained from the City of Chicago's website, which serves as an open repository of valuable information.

To determine the severity of accidents, classification models such as Logistic Regression, Decision Trees, and Random Forests will be employed. Through extensive evaluation, the Random Forest model has been identified as the optimal choice, exhibiting remarkable performance metrics. It achieves an accuracy, precision, and recall score of 94%, 94%, and 91% respectively, enabling accurate prediction of accident severity.

Once the severity of accidents is determined, the next step is to identify the parameters that have the most significant impact on accident severity. This analysis will provide valuable insights into the key factors contributing to accidents. Multiple linear regression will be used to assign a risk score to each location based on these influential parameters.

The project also involves the application of K-Means clustering technique to identify distinct areas or clusters based on the geographical coordinates and risk scores of each location. This clustering process aids in the categorization and identification of regions with similar characteristics and risk levels, enhancing the accuracy of the navigation system.

The machine learning model's outputs will be integrated with the open route service (ORS), an external service that offers routing and mapping functionalities. Depending on the user's chosen mode of transportation, the system will provide a route map, step-by-step instructions, and estimated travel time for each stage of the journey. This integration ensures that users can travel safely while minimizing the likelihood of encountering traffic accidents.

## **Extracting the data from the following files:**
It is worth mentioning that the project extracts data from the following files available on the City of Chicago's website:

1) Daily Accident Detail Report: Contains detailed information about daily accidents.

[File Link](https://data.cityofchicago.org/api/views/85ca-t3if/rows.csv): Daily Accident Detail Report

2) Vehicle Details: Provides specific details about the vehicles involved in the accidents.

[File Link](https://data.cityofchicago.org/api/views/68nd-jvt3/rows.csv): Vehicle Details

3) People Details: Contains information about the individuals involved in the accidents.

[File Link](https://data.cityofchicago.org/api/views/u6pd-qa9d/rows.csv): People Details

By leveraging the insights gained from these datasets and the developed machine learning model, the navigation system can be implemented in real-time. This implementation aims to ensure that individuals can travel safely while minimizing the occurrence of traffic accidents.
