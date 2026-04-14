# # Ecommerce Customers Analysis using Linear Regression

## 📌 Lab Overview

This lab applies Linear Regression to analyze an Ecommerce dataset and predict customer yearly spending.

---

## 📊 Dataset

The dataset includes information about customers such as:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent

---

## ⚙️ Steps Performed

### 1. Data Loading

Loaded the dataset using pandas.

### 2. Data Exploration

Used:

* head()
* info()
* describe()

### 3. Data Cleaning

Checked for missing values and found none.

### 4. Feature Engineering

Removed non-numerical columns:

* Email
* Address
* Avatar

### 5. Data Visualization

* Pairplot
* Scatter plots
* Heatmap

### 6. Model Training

Used Linear Regression model from sklearn.

### 7. Model Evaluation

Evaluated using:

* MAE
* MSE
* RMSE


## 📈 Results

* The model performed well with low error.
* Length of Membership is the most important feature affecting spending.


## 🧠 Conclusion

Customers who stay longer tend to spend more, making membership duration the strongest predictor of yearly spending.

## 🛠️ Tools Used

* Python
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn

