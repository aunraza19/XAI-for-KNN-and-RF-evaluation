# Breast Cancer Classification with KNN and Explainable AI (XAI)

## Project Overview
This project focuses on building a machine learning model for **Breast Cancer Classification** using the **Breast Cancer Wisconsin dataset**.  
While traditional ML models can achieve high accuracy, they often act like "black boxes" making predictions without clear explanations.  

👉 To solve this, the project combines **K-Nearest Neighbors (KNN)** with **Explainable AI (XAI)** techniques like **LIME**, ensuring the model is not only accurate but also **interpretable**.

---

## Objectives
- Implement a **KNN classifier** for breast cancer prediction.  
- Evaluate performance using **cross-validation** and **hyperparameter tuning**.  
- Compare results with an alternative model (**Random Forest**).  
- Visualize key results with **accuracy curves, confusion matrices, and ROC curves**.  
- Apply **Explainable AI (LIME)** to understand why the model makes certain predictions.  

---

## Dataset
- **Name:** Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))  
- **Features:** 30 numeric features describing cell nuclei characteristics  
- **Target:**  
  - `0` → Malignant (cancerous)  
  - `1` → Benign (non-cancerous)  

---

## Techniques & Workflow
1. **Data Preprocessing**
   - Standard scaling applied for uniform feature distribution.  

2. **Model Implementation**
   - **KNN Classifier** trained and tuned with different values of `k`.  
   - Performance analyzed using **accuracy score**, **cross-validation**, and **hyperparameter tuning**.  

3. **Model Evaluation**
   - Confusion Matrix  
   - Accuracy vs. K graph  
   - ROC Curve & AUC  

4. **Model Comparison**
   - Benchmarked against a **Random Forest classifier** for validation.  

5. **Explainable AI (XAI)**
   - **LIME (Local Interpretable Model-Agnostic Explanations)** applied to explain individual predictions.  
   - Highlighted **top contributing features** for each test sample.  

---

## Results & Insights
- **KNN achieved ~95–96% accuracy** after hyperparameter tuning.  
- Random Forest provided a strong baseline for comparison.  
- Performance graphs showed:
  - Optimal K value improves generalization.  
  - ROC curve confirmed strong separability between classes.  
- **XAI with LIME** revealed the **key features influencing predictions**, making the model more **transparent and trustworthy**.  

---

## Example Visuals
- Accuracy vs K curve  
- Confusion Matrix  
- ROC Curve  
- LIME explanation plot  

*(These graphs are available in the notebook.)*  

---

1. Clone the repo:
   ```bash
   git clone https://github.com/aunraza19/XAI-for-KNN-andRf-evaluation.git
   
Run the Jupyter notebook:

## Acknowledgements

This project was developed as part of a machine learning portfolio to demonstrate model building, evaluation, and explainability techniques in healthcare-related datasets.
