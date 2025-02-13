# Wildfire-Data-Analysis-and-Prediction-Using-Machine-Learning

The project focuses on analyzing and predicting wildfire incidents using historical fire data. It processes a dataset (California_Fire_Incidents.csv) containing various attributes such as burned acres, administrative units, affected counties, and fire start dates. The primary objective is to clean, analyze, and visualize wildfire data to identify trends and assess factors contributing to fire severity. By leveraging data preprocessing techniques, the project ensures data quality for further exploration and predictive modeling.

To enhance data usability, the project removes irrelevant columns, handles missing values, and converts date attributes into a structured format. Numerical attributes, such as the number of structures destroyed, are filled with zero where missing, assuming unreported cases. This preprocessing step ensures the dataset is structured for effective analysis. Exploratory data analysis (EDA) is conducted using pandas and visualization libraries to uncover patterns in wildfire occurrences, including seasonal trends and geographic distributions.

The project also applies machine learning techniques to predict wildfire severity based on historical data. Various models, such as decision trees and random forests, are trained to estimate the extent of damage in terms of acres burned. Model performance is evaluated using key metrics such as accuracy and error rates to determine their predictive capabilities. Feature importance analysis helps identify the most significant factors influencing fire spread and intensity.

By providing a structured approach to wildfire data analysis, this project contributes to improving early detection and response strategies. The insights gained from the analysis can help authorities allocate resources more efficiently and develop preventive measures to mitigate wildfire risks. The predictive modeling aspect enhances preparedness by forecasting potential fire severity, making it a valuable tool for disaster management and environmental protection
