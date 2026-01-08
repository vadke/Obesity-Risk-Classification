# 🏥 Obesity Risk Classification & Modeling

## 📌 Business Overview
In the healthcare sector, preventative medicine is far more cost-effective than treatment. This project aims to assist public health officials by building a predictive model that identifies individuals at high risk of obesity based on non-invasive lifestyle surveys (e.g., diet, transportation mode, physical activity).

## 📊 Technical Approach
* **Data Source:** `ObesityDataSet.csv` (2,100+ records).
* **Preprocessing:** * Encoding categorical variables (One-Hot & Label Encoding).
    * **Handling Imbalance:** Used **SMOTE** to generate synthetic samples for under-represented weight classes.
* **Models Trained:** Random Forest, Decision Tree, KNN.
* **Evaluation:** Accuracy Score, Confusion Matrix.

## 📈 Key Findings
1.  **Family History is Critical:** Individuals with a family history of overweight issues had a significantly higher probability of being classified as "Obese."
2.  **Transportation Impact:** People using "Automobiles" showed higher obesity rates compared to those using "Public Transportation" or "Walking."
3.  **Model Performance:** Random Forest outperformed other models, successfully handling the multi-class nature of the target variable.

## 🛠 Tools Used
* **Python:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn, Imbalanced-learn (SMOTE)
* **Visualization:** Seaborn, Matplotlib

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install -r requirements.txt`
3.  Run `Obesity_Risk_Analysis.ipynb` in Jupyter Notebook.
