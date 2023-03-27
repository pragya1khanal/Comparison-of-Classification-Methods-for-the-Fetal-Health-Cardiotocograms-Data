# Comparison-of-Classification-Methods-for-the-Fetal-Health-Cardiotocograms-Data
This project’s main goal was to build classification models to identify the status of pathological risk associated with the developing fetus using cardiotocograms data. 
To perform the analysis, data provided by UCI Machine Learning Repository was used. 
To solve multinomial classification problem, methods such as multinomial logistic regression, Principal Component Analysis applied multinomial logistic regression, KNN, 
Decision tree, Random Forest, Bagging and Neural networks were implemented to predict if the fetus with given cardiotocogram is developing abnormalities.

Correlation plot between predictor variables.

![image](https://user-images.githubusercontent.com/111830763/228022920-57e78934-2810-49a7-aa65-2eaba75db2ce.png)

Decision Tree

![image](https://user-images.githubusercontent.com/111830763/228025881-e7344527-b3f2-4a28-b5cd-86374d160724.png)

Neural Network

![image](https://user-images.githubusercontent.com/111830763/228026083-849531c2-50c3-4365-93bd-d03fff21d4ec.png)

Comparision chart (On the basis of Kappa Values)

![image](https://user-images.githubusercontent.com/111830763/228033493-2195b743-1030-4a08-8a21-07d07a43a04e.png)

From comparison table of all model test metrics, Bagging is the top performer followed by Random Forest and Neural Net.
