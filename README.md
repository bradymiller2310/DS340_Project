This DS 340W term project was done by myself and Sam Cerimele. Heart disease is a leading cause of mortality worldwide, making accurate prediction critical for early intervention and improved patient outcomes. Our project focuses on enhancing heart disease predictions using a Convolutional Neural Network (CNN) combined with ensemble learning through bagging. We utilized a dataset of 70,000 rows with 12 features, after eliminating one redundant feature. During preprocessing, we addressed data quality by trimming implausible blood pressure values (systolic and diastolic). To optimize our model, we performed hyperparameter tuning, specifically adjusting the number of neurons and dropout rates in the dense layers, and used a sigmoid activation function for generating predictions. In addition to training on the full dataset, we split the data by gender (males and females) to analyze how features impact predictions differently across genders. To further interpret our results, we employed SHAP and LIME to create visualizations that highlight both general feature impacts and feature importance at the individual prediction level, providing insights into the factors influencing heart disease predictions.

The files that we used for our analysis are:
1)**Ensemble_CNN_w_bagging.ipynb** 
This file contains our exploratory data analysis (EDA), data preprocessing, creation of the CNN model for the entire dataset, as well as its hyperparameter tuning, bagging, and SHAP and LIME visual explanations.

2) **CNN_bagging_males.ipynb**
This file contains the model creation, hyperparameter tuning and feature importance analysis for the **male** only dataset that was created and saved from the _Ensemble_CNN_w_bagging.ipynb_ file.

3) **CNN_bagging_females.ipynb**
This file contains the model creation, hyperparameter tuning and feature importance analysis for the **female** only dataset that was created and saved from the _Ensemble_CNN_w_bagging.ipynb_ file.

