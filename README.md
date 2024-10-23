# From-chemistry-to-quality: Predicting Wine Quality Using past customer ratings and wine chemical Properties

The aim of this project is to experiment with various classification models in order to predict the quality of wine based on past customer ratings and using the following wine chemical properties: fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulphur dioxide, total sulphur dioxide, density, pH, sulphates, and alcohol.

The dataset was obtained from the UCI Machine Learning Repository.  The two datasets pertain to the red and white varieties of the Portuguese "Vinho Verde" wine. The red wine dataset contains a total of 1,599
instances, whereas the white wine dataset comprises 4,898 instances. Both datasets feature 12 columns, each based on physicochemical tests.

To perform the analysis and train machine learning models, I merged the red and white wine datasets. Before merging, I created a new column to indicate whether the wine is red or white. 

The chemical properties that shows a positive relationship with quality are:

- alcohol
- residual sugar -
- total sulfur dioxide
- sulphate
- ph
- free sulfur dioxide
- citric acid

These features will be used for training the following models were used for model experimentation:

- Logistic Regression
- SVC
- Decision Tree
- KNN
- Random Forest
