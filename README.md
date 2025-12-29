# Logistic Regression

This project implements a **Logistic Regression classification model** to predict whether a user will **click on an online advertisement** based on demographic and behavioral features.  
The project demonstrates **proper EDA, preprocessing with pipelines, model training, evaluation, and interpretation** following machine-learning best practices.

---

## 📌 Problem Statement

The goal is to predict whether the user **clicked on an advertisement** (`Clicked on Ad = 1`) or not (`0`) from the given data.

This is a **binary classification problem**, making Logistic Regression a suitable baseline model.

---
## 📁 Project Structure
```
logistic_regression/
│
├── data/
│ └── advertising.csv # Dataset
└──logistic_regression.ipynb

```
---
## 📊 Dataset Information

The dataset consists of multiple features related to user activity and demographics:

| Feature                      | Description                                           |
| ---------------------------- | ----------------------------------------------------- |
| **Daily Time Spent on Site** | Time (in minutes) a user spends daily on the website. |
| **Age**                      | Age of the user.                                      |
| **Area Income**              | Average income of the user's geographical area.       |
| **Daily Internet Usage**     | Time (in minutes) spent online daily.                 |
| **Ad Topic Line**            | Headline of the advertisement.                        |
| **City**                     | User's city.                                          |
| **Male**                     | Gender indicator (1 = Male, 0 = Female).              |
| **Country**                  | User's country.                                       |
| **Timestamp**                | Time when the user was shown the ad.                  |
| **Clicked on Ad**            | Target variable (1 = Clicked, 0 = Did not click).     |

---

## 🧪 Technologies Used

- Python

- Pandas & NumPy

- Scikit-learn

- Matplotlib & Seaborn

- Jupyter Notebook

---

## ⚙️ Data Preprocessing

Before feeding the data into the model, we perform:

🔹 **Handling Missing Values**: Checking and imputing missing values.
🔹 **Encoding Categorical Features**: Converting categorical variables into numerical form.
🔹 **Feature Scaling**: Standardizing numerical features to improve model performance.

---
## 🤖 Model Development

We implement **Logistic Regression** using `sklearn`:

1️⃣ **Data Splitting**: Splitting the dataset into training and testing sets.
2️⃣ **Model Training**: Fitting the logistic regression model to the training data.
3️⃣ **Hyperparameter Tuning**: Adjusting the regularization parameter (`C`) for optimal performance.

---

## 📝 Model Evaluation

📌 **Performance Metrics Used:**

- **Accuracy Score**: Overall correctness of predictions.
- **Confusion Matrix**: Evaluates true positives, true negatives, false positives, and false negatives.
- **Classification Report**: Shows precision, recall, and F1-score.
- **ROC Curve & AUC Score**: Measures how well the model distinguishes between classes.

---
## ✅ Key Takeaways

- Logistic Regression performs well as a baseline classifier

- Feature scaling is mandatory for gradient-based models

- Pipelines prevent data leakage and simplify ML workflows

---
## 🙌 Author

Nishant Chandra Verma


