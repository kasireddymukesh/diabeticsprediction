**Project Overview — Diabetes Prediction System**

This project builds a **machine learning model to predict whether a person is diabetic or non-diabetic** using medical data from the **PIMA Indians Diabetes Dataset**.

---

### 🔹 Objective

To develop a predictive system that analyzes patient health parameters and classifies them as:

* **0 → Non-Diabetic**
* **1 → Diabetic**

---

### 🔹 Dataset

The model uses the **PIMA Diabetes dataset**, which contains **8 medical features**, such as:

* Pregnancies
* Glucose level
* Blood pressure
* Skin thickness
* Insulin
* BMI
* Diabetes pedigree function
* Age

---

### 🔹 Project Workflow

1. **Import Libraries** – NumPy, Pandas, Scikit-learn modules.
2. **Data Collection** – Load dataset using Pandas.
3. **Data Analysis**

   * View dataset shape and sample rows.
   * Check statistical measures.
   * Count diabetic vs non-diabetic cases.
4. **Data Preprocessing**

   * Separate features (X) and target (Y).
   * Standardize data using `StandardScaler`.
5. **Train–Test Split**

   * 80% training data
   * 20% testing data
   * Stratified split to maintain class balance.
6. **Model Training**

   * Uses **Support Vector Machine (SVM)** with a **linear kernel**.
7. **Evaluation**

   * Accuracy calculated for both training and testing datasets.
8. **Prediction System**

   * Accepts new patient data (8 values).
   * Reshapes input and predicts diabetic status.

---

### 🔹 Output

The system produces:

* Training accuracy score
* Testing accuracy score
* Prediction for new input patient data

---

