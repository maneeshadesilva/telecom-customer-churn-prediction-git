# Telecom Customer Churn Prediction

This project demonstrates a **machine learning approach to predicting customer churn** in the telecom industry using Python. The main goal is to analyze customer data and build predictive models that identify customers who are likely to leave the service, helping businesses take proactive measures to retain them.

---

## Project Structure

telecom-customer-churn-prediction-git/
├── notebooks/ # Jupyter notebooks for exploration and modeling
│ └── Telecom Customer Churn Prediction My Version.ipynb
└── README.md # This file
To run the notebooks:

1. Download the dataset from Kaggle.
2. Place the CSV file(s) inside the `data/` folder.
3. Make sure the file names match those used in the notebooks.

---

## Technologies & Libraries

- Python 3.x  
- Jupyter Notebook  
- pandas, numpy, matplotlib, seaborn  
- scikit-learn for machine learning models  
- pickle for saving and loading trained models  

---

## How to Run

1. Clone the repository:

git clone https://github.com/maneeshadesilva/telecom-customer-churn-prediction-git.git
cd telecom-customer-churn-prediction-git 


2. Install dependencies:
pip install -r requirements.txt


3. Open the notebook:
jupyter notebook notebooks/Telecom Customer Churn Prediction My Version.ipynb


4. Follow the notebook to explore data, train models, and evaluate performance.
You will need to provide your own dataset in a data/ folder if you want to run the full analysis.



## Machine Learning Models Used

This project includes the following 5 machine learning models for predicting customer churn:
1. XG Boost Model.
2. Decision Tree Model.
3. Random Forest Classifier Model.
4. Logistic Regression Model
5. Neural Network Model. 


## Project Highlights

Exploratory Data Analysis (EDA): Understand customer behavior and trends.
Data Preprocessing: Handle missing values, encode categorical features, scale numerical data.
Model Training & Evaluation: Train multiple models and compare their performance using metrics like accuracy, precision, recall, F1-score, and confusion matrices.
Model Persistence: Save trained models for future use.
Support Vector Machine (SVM) – Effective for high-dimensional feature spaces.
Gradient Boosting Classifier – Boosting technique for high-performance predictions.
Decision Tree Classifier – Simple and interpretable tree-based model.


Created by Maneesha De Silva.
