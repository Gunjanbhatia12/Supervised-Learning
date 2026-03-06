# Supervised-Learning
# Logistic Regression - Pass/Fail Prediction Model

## 📌 Project Overview

This project demonstrates the implementation of a **Logistic Regression Machine Learning model** using Python.
The model predicts whether a student will **Pass or Fail** based on the **number of hours studied**.

Logistic Regression is widely used for **binary classification problems**, where the output has two possible classes (e.g., Yes/No, Pass/Fail, Fraud/Not Fraud).

This notebook walks through:

* Creating a dataset
* Training a Logistic Regression model
* Making predictions
* Understanding probability outputs

---

## 🎯 Objectives

* Understand the concept of **Logistic Regression**
* Implement a **binary classification model**
* Train a model using **Scikit-learn**
* Predict results using trained data
* Interpret probability outputs

---

## 🧠 What is Logistic Regression?

Logistic Regression is a **supervised machine learning algorithm** used for **classification tasks**.

Unlike Linear Regression, which predicts continuous values, Logistic Regression predicts **probabilities** that map to discrete classes.

The logistic function (Sigmoid Function) is used to convert output into probabilities between **0 and 1**.

### Logistic Function

P(Y = 1) = 1 / (1 + e^-(b₀ + b₁X))

Where:

* **P(Y=1)** → Probability of positive class
* **b₀** → Intercept
* **b₁** → Coefficient
* **X** → Input feature

---

## 📊 Dataset Description

A simple dataset is used where:

| Hours Studied | Result |
| ------------- | ------ |
| 1             | Fail   |
| 2             | Fail   |
| 3             | Fail   |
| 4             | Pass   |
| 5             | Pass   |
| 6             | Pass   |

### Target Encoding

* **0 → Fail**
* **1 → Pass**

---

## ⚙️ Technologies Used

* Python
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 📂 Project Structure

```
Logistic-Regression-Pass-Fail
│
├── logisticregression.ipynb
├── README.md
```

---

## 🚀 Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/logistic-regression-project.git
```

### Step 2: Navigate to the Project Folder

```bash
cd logistic-regression-project
```

### Step 3: Install Required Libraries

```bash
pip install numpy scikit-learn jupyter
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```
logisticregression.ipynb
```

Run all cells to train the model and view predictions.

---

## 🔍 Model Implementation Steps

1. Import required libraries
2. Create the dataset
3. Split input and output variables
4. Train Logistic Regression model
5. Make predictions
6. Display probability results

---

## 📈 Example Prediction

Input:

```
Hours Studied = 3.5
```

Output:

```
Prediction: Pass
Probability: [Fail %, Pass %]
```

Example Output:

```
Prediction (0 = Fail, 1 = Pass): [1]
Probability: [[0.42 0.58]]
```

Meaning:

* **42% chance of failing**
* **58% chance of passing**

---

## 📊 Visualization (Optional)

You can visualize the decision boundary using matplotlib to understand how the model separates classes.

Example plot:

* X-axis → Hours Studied
* Y-axis → Pass/Fail probability

---

## 💡 Applications of Logistic Regression

Logistic Regression is widely used in many real-world applications such as:

* Credit Card Fraud Detection
* Medical Diagnosis
* Spam Email Detection
* Customer Churn Prediction
* Loan Approval Systems

---

## 🛠 Future Improvements

Possible improvements to this project:

* Use a larger real-world dataset
* Add visualization using Matplotlib
* Implement train-test split
* Evaluate model using accuracy metrics
* Deploy model using Streamlit

---

## 📚 Learning Outcomes

After completing this project you will understand:

* Binary classification problems
* Logistic regression algorithm
* Probability-based prediction
* Model training with Scikit-learn

---

## 👨‍💻 Author

**Gunjan**

B.Tech in CSE
---
