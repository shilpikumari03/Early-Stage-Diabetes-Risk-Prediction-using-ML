Early Stage Diabetes Risk Prediction

Project Overview
This project aims to predict the risk of early-stage diabetes utilizing machine learning techniques. The dataset used in this project was collected from patients of Sylhet Diabetes Hospital in Sylhet, Bangladesh, with approval from a doctor.

Dataset Information
The dataset contains several attributes related to patients, including age, sex, and the presence of various symptoms such as polyuria, polydipsia, and weakness. The dataset also includes the diagnosis of diabetes as either positive or negative.

Project Structure
The project is divided into two Jupyter notebooks:

DiabetesRiskPrediction_DataPreprocessing.ipynb: This notebook handles data preprocessing tasks, such as dealing with missing values, encoding categorical variables, and splitting the dataset into training and testing sets. The preprocessed datasets are saved and exported as X_train, X_test, y_train, and y_test for further modeling.

DiabetesRiskPrediction_models.ipynb: In this notebook, various machine learning models are implemented, including logistic regression, support vector machine (SVM), decision trees, and deep neural networks. Hyperparameter tuning is performed to optimize the models, and the performance metric chosen for evaluation is recall, which measures the true positive rate. The deep neural network model achieved the best performance with an impressive recall score of 98.9%

Instructions for Running the Project

To run this project on your local machine, follow these steps:

Clone the repository from GitHub: [GitHub Repository URL]

Install the required libraries and dependencies listed in the requirements.txt file.

Open the Jupyter notebooks in the following order:

DiabetesRiskPrediction_DataPreprocessing.ipynb
DiabetesRiskPrediction_models.ipynb
Run each notebook cell sequentially to preprocess the data, train the machine learning models, and evaluate their performance.

Feel free to experiment with hyperparameters or try different models to enhance the model's performance further.

Conclusion
This project showcases the application of machine learning techniques for early-stage diabetes risk prediction. The deep neural network model stood out, achieving the highest performance with a recall score of 98.9%. This repository's provided code and datasets can serve as a reference for similar projects or further development. Feel free to reach out if you have any questions or need assistance. Happy coding!
