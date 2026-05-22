# Water Potability Prediction using SVM & Snowflake

## 📌 Overview
This project predicts **water potability** (whether water is safe to drink) using a **Support Vector Machine (SVM)** classifier. The dataset is stored and managed in **Snowflake**, enabling scalable data handling and efficient queries.

## ⚙️ Workflow
1. Connect to Snowflake and fetch the water quality dataset.
2. Handle missing values using `SimpleImputer`.
3. Apply **Winsorization** to reduce outlier effects.
4. Standardize features with `StandardScaler`.
5. Train an **SVM (linear kernel)** classifier.
6. Evaluate performance using **accuracy score**.

## 🛠️ Tech Stack
- **Python**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn  
- **Snowflake**: Data storage & retrieval  
- **Machine Learning**: Support Vector Machine (SVM)

## 📊 Output
The trained SVM model classifies water samples as **potable (safe to drink)** or **non-potable**, with accuracy evaluated on test data.

