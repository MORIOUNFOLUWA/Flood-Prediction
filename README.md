# Flood-Prediction
The goal of this project was to develop machine learning models to predict floods in Bangladesh using historical weather data from 1948-2013. The dataset was obtained from the Bangladesh Meteorological Department and contained over 20,000 observations on rainfall, cloud coverage, temperature, humidity, and flood status. 

Data pre-processing steps included handling missing values, encoding the flood status as a binary target variable, splitting data into train and test sets, and feature selection using correlation analysis. Rainfall and cloud coverage were identified as relevant predictors. Exploratory analysis using plots revealed trends between higher rainfall/cloud coverage and increased flooding.

Three supervised learning models were developed - logistic regression, decision tree, and K-nearest neighbors (KNN). The models were trained on 70% of data and evaluated on the remaining 30% using accuracy, precision, recall, and F1 score metrics. 

Among the models, KNN achieved the highest accuracy of 94% in predicting flood status on test data. The optimal K value was 15. This model was chosen as the best performing for flood prediction based on its balanced precision and recall scores. 

Overall, the project demonstrated that machine learning techniques can uncover patterns in meteorological data to predict floods. The models developed provide a foundation that can be built upon with more recent, real-time data to improve predictive monitoring of floods in flood-prone regions like Bangladesh.
