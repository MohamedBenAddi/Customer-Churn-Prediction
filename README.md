
# Customer Churn Prediction
Losing customers is a major challenge for businesses, especially in banking, leading to lost revenue and lower satisfaction. Understanding customer behavior can help businesses keep their customers longer.

This project aims to predict customer churn in the banking sector by identifying key factors that cause customers to leave. Using these insights, businesses can take action to keep more customers and improve satisfaction.


## Install the requirements
* Make sure you use Python 3.

* Install the requirements using ``` pip install -r requirements.txt ```.

## Project Steps

**1. Data Collection**

* I collected data from this [Kaggle dataset](https://www.kaggle.com/datasets/anwarsan/credit-card-bank-churn), which contains a CSV file with detailed credit card bank data.

**2. Data Preprocessing**

* I removed unnecessary columns.
* I converted the target column from categorical values to numerical ones.

**3. Exploratory Data Analysis (EDA)**

* Exploring the factors that contribute to customer churn.

**4. Feature engineering**

* I applied one-hot encoding to convert categorical columns into numerical format, so they can be used by the model.

**5. Imbalanced Data**

* Since the data is imbalanced, which could affect the model's performance, I will balance it using the SMOTE method.

**6. Training the model**

* I used a Random Forest model to classify whether a customer will churn or not.

**7. Test & Evaluation**

* To evaluate the model's performance, I used a confusion matrix, accuracy, and precision.

* To further evaluate the model, I applied cross-validation.

## Results

* The number of transactions in the last 12 months greatly affects whether a customer will churn.

* The total revolving balance on a credit card also influences customer churn.

* By using only 8 out of the original 19 features, the machine learning model achieved an impressive accuracy of 94%. (model_final.pkl)