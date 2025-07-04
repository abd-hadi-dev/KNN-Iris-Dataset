# 🧠 Task 6: K-Nearest Neighbors (KNN) Classification

This project is part of the AI & ML Internship program. The goal is to implement and understand the **K-Nearest Neighbors (KNN)** classification algorithm using Scikit-learn, applied on a classification dataset.

---

## 📁 Dataset

The dataset used for this task is provided in the file `archive.zip`. It is a classification dataset, which was preprocessed and used to train and evaluate the KNN model.

---

## 📌 What Was Done

### 1. Data Preprocessing
- Loaded the dataset using Pandas.
- Checked and handled any missing values.
- Split the dataset into features (X) and labels (y).

### 2. Normalization
- Normalized the feature values using `StandardScaler`.
- Normalization is important in KNN since it relies on distance metrics.

### 3. KNN Model Training
- Used `KNeighborsClassifier` from Scikit-learn.
- Trained the model using different values of **K** (like 3, 5, and 7).
- Chose the best K based on accuracy and performance metrics.

### 4. Evaluation
- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### 5. Visualization
- Plotted decision boundaries using Matplotlib.
- Visualized how KNN separates different classes based on feature space.

---

## 📊 Results

| K Value | Accuracy |
|--------|----------|
|   3    |  XX.X%   |
|   5    |  XX.X%   |
|   7    |  XX.X%   |

> Replace `XX.X%` with actual accuracy values from your notebook.

---

## ❓ Interview Questions Covered

- How does KNN work?
- Why is normalization important in KNN?
- How to choose the right K value?
- What is the time complexity of KNN?
- What are the pros and cons of KNN?
- Is KNN sensitive to noise?
- How does KNN handle multi-class classification?
- What is the role of distance metrics in KNN?

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🔗 Submission

- **GitHub Repository Link:** *[Your GitHub repo link here]*
- **Task Submission Form:** [https://forms.gle/8Gm83s53KbyXs3Ne9](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## ✅ Output Files Included

- `KNN_Classifier.ipynb` – Jupyter notebook with complete code
- `archive/` – Extracted dataset folder from archive.zip
- `README.md` – This documentation file
