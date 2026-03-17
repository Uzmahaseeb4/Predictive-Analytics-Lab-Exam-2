# 📊 Predictive Analytics Lab Exam-2

## 📌 Objective

The objective of this project is to perform a **classification task** using machine learning techniques. The workflow includes Exploratory Data Analysis (EDA), data preprocessing, model building, decision boundary visualization, and performance evaluation.

---

## 📂 Dataset

* The dataset used is a **binary classification dataset**.
* The last column is considered as the **target variable**.
* It contains both numerical and (possibly) categorical features.

---

## 🔍 Exploratory Data Analysis (EDA)

The following steps were performed:

* Checked dataset shape, structure, and data types
* Identified missing values
* Analyzed class distribution
* Generated correlation heatmap for numerical features
* Visualized feature distributions and detected outliers using boxplots

---

## ⚙️ Data Preprocessing

* Handled missing values using mean imputation
* Removed outliers using the **IQR (Interquartile Range) method**
* Selected features (X) and target variable (y)
* Applied **feature scaling (StandardScaler)**
* Split dataset into training and testing sets (80:20 ratio)

---

## 🤖 Model Building

* Used **Logistic Regression** for classification
* Model trained on the training dataset
* Predictions made on the test dataset

---

## 📈 Decision Boundary Visualization

* Decision boundary plotted using the first two features
* Used meshgrid and contour plot to visualize classification regions
* Data points plotted along with predicted regions

---

## 📊 Model Evaluation

The model was evaluated using:

* **Accuracy Score**
* **Confusion Matrix**
* **Precision, Recall, and F1-score**

### 🔹 Results

* Accuracy: XX%
* Precision: XX
* Recall: XX
* F1-score: XX

*(Replace XX with actual values from your output)*

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Google Colab

---

Project Structure

```
Predictive-Analytics-Lab-Exam-2/
│── Lab_Exam_binary_classification_dataset.csv
│── notebook.ipynb
│── README.md
```

---

 Conclusion

* Logistic Regression successfully classified the data
* The model achieved reasonable performance
* Visualization helped in understanding class separation

---

 Future Improvements

* Try advanced models (SVM, Random Forest)
* Perform hyperparameter tuning
* Use feature selection techniques

---

