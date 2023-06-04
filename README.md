## **Navigation System To Avoid Accident Prone Areas Using Machine Learning Techniques**

The aim of the project is to develop a navigation system using machine learning that avoids accident-prone areas. The research data comprises of daily accident reports with location details acquired from the City of Chicago website, which is an open repository. By using classification models such as Logistic Regression, Decision Trees, and Random Forests, the severity of the accident can be determined. The optimal model determined is **Random Forest** which has an accuracy, precision, and recall, scores of **94%, 94% and 91%** respectively. Once the severity is determined, the parameters that have the greatest effect on severity will be identified. The risk score for each location will be determined based on those parameters, using **multiple linear regression**. Using the **K-Means clustering technique**, distinct areas or clusters will be identified based on the co-ordinates and the risk score of the location. The machine learning model’s outputs will be fed into the **open route service (ORS)**, and depending on the mode of transportation, the route map, instructions, and time required for each stage of the journey will be provided. The model developed in this research project can be implemented in real time to ensure people travel safely and minimize traffic accidents.


## **Extracting the data from the following files:**

Daily Accident Detail Report = https://data.cityofchicago.org/api/views/85ca-t3if/rows.csv

Details about the Vehicles involved in the Accident = https://data.cityofchicago.org/api/views/68nd-jvt3/rows.csv

Details about the People involved in the Accident= https://data.cityofchicago.org/api/views/u6pd-qa9d/rows.csv
