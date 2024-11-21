**Overview**


This DS 340W term project was done by myself and Sam Cerimele. Heart disease is a leading cause of mortality worldwide, making accurate prediction critical for early intervention and improved patient outcomes. Our project focuses on enhancing heart disease predictions using a Convolutional Neural Network (CNN) combined with ensemble learning through bagging. We utilized a dataset of 70,000 rows with 12 features, after eliminating one redundant feature. During preprocessing, we addressed data quality by trimming implausible blood pressure values (systolic and diastolic). To optimize our model, we performed hyperparameter tuning, specifically adjusting the number of neurons and dropout rates in the dense layers, and used a sigmoid activation function for generating predictions. In addition to training on the full dataset, we split the data by gender (males and females) to analyze how features impact predictions differently across genders. To further interpret our results, we employed SHAP and LIME to create visualizations that highlight both general feature impacts and feature importance at the individual prediction level, providing insights into the factors influencing heart disease predictions. 



**The files that we used for our analysis are:**

1) **Ensemble_CNN_w_bagging.ipynb**
    
This file contains our exploratory data analysis (EDA), data preprocessing, creation of the CNN model for the entire dataset, as well as its hyperparameter tuning, bagging, and SHAP and LIME visual explanations.

2) **CNN_bagging_males.ipynb**
   
This file contains the model creation, hyperparameter tuning and feature importance analysis for the **male** only dataset that was created and saved from the _Ensemble_CNN_w_bagging.ipynb_ file.

3) **CNN_bagging_females.ipynb**
   
This file contains the model creation, hyperparameter tuning and feature importance analysis for the **female** only dataset that was created and saved from the _Ensemble_CNN_w_bagging.ipynb_ file.

4) **cardio_train.csv**
   
This csv contains the dataset that we used for our analysis.

_All other files shown (marked with **) were the original code files from the repository we inherited from our first parent paper..._


**Novelty Code Contributions**

Most of the code in those 3 files were created by us. Most of the EDA was provided in the code set we retrieved from our first parent paper (correlation matrices, feature distribution histograms, bar charts), but the CNN, hyperparameter tuning, bagging and feature importance (SHAP & LIME) were all things that we added ourselves. We based our CNN around a CNN that we had found in one of the papers that we analyzed, but made some slight tweaks to it, to adapt to our use case and any problems we encountered.



**Literature Review Source Links**

1) https://arxiv.org/abs/2008.02731
  
2) https://www.sciencedirect.com/science/article/pii/S235291482100143X?ref=pdf_download&fr=RR-2&rr=8e0802a1187d505a

3) https://link.springer.com/content/pdf/10.1007/s13369-020-05105-1.pdf

