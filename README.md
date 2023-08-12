# Predicting Early Stage Diabetes Risk using Machine Learning

This project is dedicated to forecasting the risk of early-stage diabetes through the application of advanced machine learning methods. The dataset employed for this project originates from patients at the Sylhet Diabetes Hospital in Sylhet, Bangladesh, and has been approved by a medical professional.



## Dataset Overview
The dataset used for this project can be accessed through the following link: [Early Stage Diabetes Risk Prediction Dataset](https://www.kaggle.com/datasets/ishandutta/early-stage-diabetes-risk-prediction-dataset)

The dataset encompasses the following attributes:

1. Age: Age of the patient (ranging from 20 to 65)
2. Sex: Gender of the patient (1 for Male, 2 for Female)
3. Polyuria: Presence of polyuria symptom (1 for Yes, 2 for No)
4. Polydipsia: Presence of polydipsia symptom (1 for Yes, 2 for No)
5. Sudden Weight Loss: Presence of sudden weight loss symptom (1 for Yes, 2 for No)
6. Weakness: Presence of weakness symptom (1 for Yes, 2 for No)
7. Polyphagia: Presence of polyphagia symptom (1 for Yes, 2 for No)
8. Genital Thrush: Presence of genital thrush symptom (1 for Yes, 2 for No)
9. Visual Blurring: Presence of visual blurring symptom (1 for Yes, 2 for No)
10. Itching: Presence of itching symptom (1 for Yes, 2 for No)
11. Irritability: Presence of irritability symptom (1 for Yes, 2 for No)
12. Delayed Healing: Presence of delayed healing symptom (1 for Yes, 2 for No)
13. Partial Paresis: Presence of partial paresis symptom (1 for Yes, 2 for No)
14. Muscle Stiffness: Presence of muscle stiffness symptom (1 for Yes, 2 for No)
15. Alopecia: Presence of alopecia symptom (1 for Yes, 2 for No)
16. Obesity: Presence of obesity symptom (1 for Yes, 2 for No)
17. Class: Diabetes diagnosis (1 for Positive, 2 for Negative)

## Project Structure

This project is structured into two Jupyter notebooks:

1. **DiabetesRiskPrediction_DataPreprocessing.ipynb**: This notebook is dedicated to data preprocessing tasks, including handling missing data, encoding categorical variables, and dividing the dataset into training and testing subsets. The processed datasets are stored and exported as X_train, X_test, y_train, and y_test for subsequent modeling.

2. **DiabetesRiskPrediction_models.ipynb**: In this notebook, diverse machine learning models are implemented, encompassing logistic regression, support vector machines (SVM), decision trees, and deep neural networks, all of which utilize preprocessed datasets. Hyperparameter optimization is carried out to fine-tune the models. The chosen performance metric for model evaluation is recall, which quantifies the true positive rate. Remarkably, the deep neural network model achieved the highest performance, boasting a recall score of 98.9%.

## Running the Project

To execute this project on your local machine, adhere to the ensuing steps:

1. Clone the GitHub repository: https://github.com/shilpikumari03/Early-Stage-Diabetes-Risk-Prediction-using-ML

2. Install the necessary libraries and dependencies outlined in the requirements.txt file.

3. Sequentially open and run the Jupyter notebooks as follows:
- DiabetesRiskPrediction_DataPreprocessing.ipynb
- DiabetesRiskPrediction_models.ipynb

4. Execute each cell in the notebooks sequentially to preprocess the data, train the machine learning models, and evaluate their performance.

5. Feel free to experiment with hyperparameters or explore different models to further enhance the predictive capabilities of the model.

## Conclusion

This undertaking serves as a demonstrative showcase of machine learning methodologies for predicting the risk of early-stage diabetes. The standout performer among the models was the deep neural network, showcasing an impressive recall score of 98.9%. The provided repository comprises the code and datasets, serving as a reference point for further exploration and development. Should you have any queries or require clarifications, please don't hesitate to reach out.
