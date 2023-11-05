# Wine_Quality_Assessment

This project aims to predict the quality of wine based on various chemical compositions and features. It involves the use of machine learning algorithms to analyze and classify the quality of wine based on its composition. The dataset used in this project contains various attributes related to the chemical properties of wine, such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, sulphates, alcohol, and quality.

In this project, we begin by exploring the dataset and performing initial data preprocessing tasks, including handling missing values and removing duplicates. Next, we conduct an exploratory data analysis to understand the relationships between different features and the wine quality. We visualize these relationships using various plots such as bar plots and a heatmap to identify correlations between different attributes.

Following the exploratory data analysis, we preprocess the data by applying feature scaling using the StandardScaler. Subsequently, we split the dataset into training and testing sets using the train_test_split function. We then apply various classification algorithms, including Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, and Support Vector Classifier, to predict the wine quality.

Based on the results of the classification algorithms, the Support Vector Classifier is identified as the model with the highest accuracy. Therefore, we use the Support Vector Classifier to make predictions on the test dataset.

Dataset: https://www.kaggle.com/datasets/yasserh/wine-quality-dataset
