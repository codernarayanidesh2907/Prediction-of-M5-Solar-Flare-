# Prediction-of-M5-Solar-Flare- 🚀🚀
 An ML-based solar flare prediction system that analyses solar active region parameters to predict whether a solar flare may occur within the next 24 hours 🚀🚀

📌 Project Overview

 The objective is to predict whether a solar flare is likely to occur within the next 24 hours using solar active region data and Machine Learning techniques.

Solar flares are powerful bursts of energy from the Sun that can affect space weather, satellite communication, navigation systems, and other technological infrastructure. This project explores how Machine Learning can be used to analyze solar parameters and identify patterns associated with solar flare activity.

🎯 Objective

The main objective of this project is to build and compare Machine Learning models that can predict the occurrence of a solar flare within the next 24 hours.

📊 Dataset and Features

The dataset contains observational data related to solar active regions, including parameters such as:

USFLUX
TOTUSJH
TOTUSJZ
MEANALP
R_VALUE
TOTPOT
SAVNCPP
AREA_ACR
ABSNJZH

The target variable indicates whether a solar flare occurs within the specified prediction period.

⚙️ Machine Learning Workflow

The project follows the following workflow:

Data collection and understanding
Data pre-processing
Exploratory Data Analysis (EDA)
Handling class imbalance using techniques such as SMOTE and Class Weighting
Feature preparation
Training multiple Machine Learning models
Model evaluation and comparison
Hyperparameter optimization
🤖 Models Used

The following Machine Learning models were explored:

Decision Tree
Random Forest
AdaBoost
Gradient Boosting
XG Boost
📈 Model Evaluation

Since the dataset may contain class imbalance, accuracy alone may not provide a complete picture of model performance.

The models were evaluated using metrics such as:

Accuracy
Precision
Recall
F1-Score
ROC-AUC Score
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
Imbalanced-learn
XG Boost
🚀 Key Learnings

Through this project, I gained hands-on experience in:

Building an end-to-end Machine Learning pipeline
Data pre-processing and analysis
Handling imbalanced datasets
Comparing multiple classification models
Hyperparameter tuning
Evaluating models using appropriate performance metrics
Understanding the importance of responsible model evaluation in real-world applications 

Author : Narayani Deshpande 
