# Supervised Machine Learning Algorithms using Scikit-Learn

This repository demonstrates the implementation of several **Supervised Machine Learning algorithms** using **Python and Scikit-learn**.

The project focuses on both **Classification and Regression models** and provides simple notebook implementations to understand how machine learning algorithms work.

Each algorithm is implemented using **Jupyter Notebook**, allowing users to explore the full workflow of:

- Data preparation
- Model training
- Model prediction
- Model evaluation

---

# 📌 Algorithms Implemented

The repository contains implementations of the following algorithms:

## Classification Algorithms
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)
- Gradient Boosting Classifier
- K-Nearest Neighbors Classifier

## Regression Algorithms
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regressor (SVR)
- Gradient Boosting Regressor
- K-Nearest Neighbors Regressor

---

# 📂 Project Structure

```
Machine-Learning-Algorithms/
│
├── Decisiontree.ipynb
├── KNN.ipynb
├── Randomforest.ipynb
├── gradientboosting.ipynb
├── logisticregression.ipynb
├── supportvector.ipynb
│
└── README.md
```

Each notebook contains implementations of both **Classifier and Regressor models** where applicable.

---

# 🧠 Algorithm Overview

## Logistic Regression

Logistic Regression is a **supervised machine learning algorithm** mainly used for **binary classification problems**.

It predicts the probability that an input belongs to a particular class using the **sigmoid function**.

### Example Code

```python
import numpy as np
from sklearn.linear_model import LogisticRegression

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = LogisticRegression()
model.fit(X,y)

prediction = model.predict([[3.5]])

print("Prediction:",prediction)
```

---

# Decision Tree

Decision Tree is a machine learning algorithm used for both **classification and regression** tasks.

It works by splitting the dataset into smaller subsets based on feature values.

### Example

```python
from sklearn.tree import DecisionTreeClassifier
import numpy as np

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = DecisionTreeClassifier()
model.fit(X,y)

prediction = model.predict([[3.5]])

print(prediction)
```

---

# Random Forest

Random Forest is an **ensemble learning algorithm** that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### Example

```python
from sklearn.ensemble import RandomForestClassifier
import numpy as np

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = RandomForestClassifier(n_estimators=10)
model.fit(X,y)

prediction = model.predict([[3.5]])

print(prediction)
```

---

# Support Vector Machine (SVM)

Support Vector Machines are powerful algorithms used for **classification and regression tasks**.

They work by finding the **optimal hyperplane** that separates data points with the maximum margin.

### Example

```python
from sklearn.svm import SVC
import numpy as np

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = SVC(kernel='linear')
model.fit(X,y)

prediction = model.predict([[3.5])

print(prediction)
```

---

# Gradient Boosting

Gradient Boosting is an **ensemble machine learning technique** where models are built sequentially and each new model corrects the errors made by previous models.

### Example

```python
from sklearn.ensemble import GradientBoostingClassifier
import numpy as np

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = GradientBoostingClassifier()
model.fit(X,y)

prediction = model.predict([[3.5]])

print(prediction)
```

---

# K-Nearest Neighbors (KNN)

KNN is a simple algorithm that predicts the output based on the **nearest data points in the dataset**.

### Example

```python
from sklearn.neighbors import KNeighborsClassifier
import numpy as np

X = np.array([[1],[2],[3],[4],[5]])
y = np.array([0,0,0,1,1])

model = KNeighborsClassifier(n_neighbors=3)
model.fit(X,y)

prediction = model.predict([[3.5]])

print(prediction)
```

---

# ⚙️ Installation

Install the required libraries before running the notebooks.

```
pip install numpy
pip install pandas
pip install scikit-learn
pip install matplotlib
pip install jupyter
```

---

# 🚀 How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/machine-learning-algorithms.git
```

### 2️⃣ Navigate to the folder

```
cd machine-learning-algorithms
```

### 3️⃣ Start Jupyter Notebook

```
jupyter notebook
```

### 4️⃣ Open any notebook and run the cells.

---

# 🎯 Learning Outcomes

By completing this project, you will understand:

- Fundamentals of **Supervised Machine Learning**
- Difference between **Classification and Regression**
- Implementation of ML algorithms using **Scikit-learn**
- Model training and evaluation
- Practical machine learning workflow

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

# 👨‍💻 Author

**Gunjan**

Artificial Intelligence & Machine Learning Enthusiast
