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

# 🌳 Decision Tree Machine Learning Project

This project demonstrates the implementation of **Decision Tree algorithms** using Python and Scikit-Learn.  
It includes both **Decision Tree Classification** and **Decision Tree Regression** with simple example datasets to help understand how decision trees work.

---

## 📌 Project Overview

Decision Trees are supervised machine learning algorithms used for:

- **Classification** → Predicting categories (e.g., Pass/Fail)
- **Regression** → Predicting continuous values (e.g., Salary prediction)

This notebook explains the basic working of both models using small datasets.

---

## 📂 Project Structure

```
Decisiontree.ipynb   # Jupyter notebook containing model implementation
README.md            # Project documentation
```

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- Mlxtend

---

## 📦 Required Libraries

Install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend
```

Or run inside the notebook:

```python
!pip install mlxtend
```

---

## 📊 Part 1: Decision Tree Classification

This section predicts whether a student will **Pass or Fail** based on the number of **hours studied**.

### Dataset Example

| Hours Studied | Result |
|---------------|-------|
| 1 | Fail |
| 2 | Fail |
| 3 | Fail |
| 4 | Pass |
| 5 | Pass |

### Model Used

```python
DecisionTreeClassifier
```

### Output

The model predicts whether a student will pass or fail based on study hours.

---

## 📈 Part 2: Decision Tree Regression

This section predicts **salary based on experience (or input values)**.

### Dataset Example

| Input Value | Salary |
|-------------|--------|
| 1 | 10000 |
| 2 | 20000 |
| 3 | 30000 |
| 4 | 40000 |
| 5 | 50000 |

### Model Used

```python
DecisionTreeRegressor
```

### Output

The model predicts a **continuous value (salary)**.

---

## 📊 Data Visualization

The notebook also uses visualization libraries:

- **Matplotlib**
- **Seaborn**

These help in analyzing data distribution and patterns.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/decision-tree-project.git
```

### Step 2: Navigate to the Folder

```bash
cd decision-tree-project
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install numpy pandas matplotlib seaborn scikit-learn mlxtend
```

### Step 4: Run the Notebook

```bash
jupyter notebook
```

Open:

```
Decisiontree.ipynb
```

---

## 🎯 Learning Outcomes

After completing this project, you will understand:

- What a **Decision Tree** is
- Difference between **Classification and Regression**
- How to implement **DecisionTreeClassifier**
- How to implement **DecisionTreeRegressor**
- Basic **data visualization for analysis**

---

## 🚀 Future Improvements

Possible enhancements:

- Use a **real-world dataset**
- Add **tree visualization**
- Implement **Random Forest**
- Perform **hyperparameter tuning**
- Evaluate model using **accuracy and metrics**

---

# Random Forest Machine Learning Example

This project demonstrates the implementation of **Random Forest algorithms** using **Python and Scikit-learn**.  
The notebook contains examples of both **Random Forest Classification** and **Random Forest Regression** using simple sample datasets.

## 📌 Project Overview

Random Forest is a popular **ensemble machine learning algorithm** used for both classification and regression problems.  
It works by creating multiple decision trees and combining their predictions to improve accuracy and reduce overfitting.

In this notebook:
- Random Forest **Classifier** is used to predict **Pass or Fail**.
- Random Forest **Regressor** is used to predict **Salary values**.

---

## 🛠️ Technologies Used

- Python
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
RandomForest/
│
├── Randomforest.ipynb     # Main notebook containing Random Forest examples
└── README.md              # Project documentation
```

---

## ⚙️ Installation

Install the required libraries before running the notebook.

```bash
pip install numpy scikit-learn jupyter
```

---

## ▶️ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/your-username/random-forest-example.git
```

2. Navigate to the project folder

```bash
cd random-forest-example
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run the **Randomforest.ipynb** notebook.

---

# 🌳 Random Forest Classification Example

This example predicts whether a student will **Pass (1)** or **Fail (0)** based on input values.

### Code Example

```python
from sklearn.ensemble import RandomForestClassifier
import numpy as np

# Sample data
X = np.array([[1], [2], [3], [4], [5]])
y = np.array([0, 0, 0, 1, 1])  # 0 = Fail, 1 = Pass

# Create model
model = RandomForestClassifier(n_estimators=10)

# Train model
model.fit(X, y)

# Predict
prediction = model.predict([[3.5]])

print("Prediction (0=Fail, 1=Pass):", prediction)
```

---

# 📈 Random Forest Regression Example

This example predicts **salary values** based on input data.

### Code Example

```python
from sklearn.ensemble import RandomForestRegressor
import numpy as np

# Sample data
X = np.array([[1], [2], [3], [4], [5]])
y = np.array([10000, 20000, 30000, 40000, 50000])

# Create model
model = RandomForestRegressor(n_estimators=10)

# Train model
model.fit(X, y)

# Predict
prediction = model.predict([[3.5]])

print("Predicted Salary:", prediction)
```

---

## 📊 Key Concepts

- **Random Forest** is an ensemble learning technique.
- It combines multiple **decision trees**.
- Improves **accuracy and robustness**.
- Reduces **overfitting** compared to a single decision tree.

---

## 🚀 Applications of Random Forest

- Loan approval prediction
- Fraud detection
- Medical diagnosis
- Stock price prediction
- Recommendation systems

---

## 📚 Author

**Gunjan**

---

⭐ If you find this project useful, consider giving it a **star on GitHub**.

