
# **ConscienceAI**  
### *Auditing AI for Fairness, Explainability, and Ethical Compliance*

![Ethics Gauge](https://img.shields.io/badge/Ethics-Audited-blue) ![License](https://img.shields.io/badge/License-MIT-green)

---

## **📖 Overview**

**ConscienceAI** is an end-to-end machine learning pipeline that goes beyond accuracy. It assesses **AI models for ethics, fairness, and transparency**, ensuring responsible AI development

This project automates:
- **Bias Detection & Fairness Auditing**
- **Explainability using SHAP**
- **Ethics Score Calculation**
- **Policy Compliance Checklist**
- **Interactive Gauge Visualization**

---

## **🧰 Features**

| Feature | Description |
|----------|-------------|
| **Model Training** | Logistic Regression (on income prediction dataset) |
| **Explainability** | SHAP Summary Plot for feature importance |
| **Fairness Audit** | Demographic Parity & Equalized Odds analysis |
| **Ethics Scorecard** | Combines Bias, Explainability & Data Quality into a score |
| **Policy Checklist** | Ensures AI policy guidelines are followed |
| **Visualization** | Interactive Ethics Gauge via Plotly |

---

## **📦 Installation**

Run the following to install dependencies:

```bash
pip install pandas numpy scikit-learn shap fairlearn matplotlib seaborn plotly
```

---

## **📂 Dataset**

- Uses **Adult Income Dataset (UCI)** or any similar dataset with:
  - **Features:** Age, Race, Gender, Occupation, etc.
  - **Target:** Income classification (`>50K` or `<=50K`)

Upload the dataset using:

```python
from google.colab import files
uploaded = files.upload()
```

---

## **⚙️ How It Works**

1. **Preprocessing**
   - Handle nulls & encode categorical data
2. **Model Training**
   - Logistic Regression for binary classification
3. **Explainability**
   - SHAP for feature contribution visualization
4. **Fairness Audit**
   - Uses `fairlearn` to calculate bias metrics
5. **Ethics Scorecard**
   - Bias, Explainability, and Data Quality combined into a final ethics score
6. **Policy Compliance**
   - Checklist to validate responsible AI practices
7. **Visualization**
   - Plotly gauge to visualize the ethics score

---

## **📊 Ethics Score Components**

| Metric | Description |
|---------|-------------|
| **Bias Score** | Based on Demographic Parity & Equalized Odds |
| **Explainability Score** | Based on SHAP visualization availability |
| **Data Diversity Score** | Checks sensitive feature balance |

---

## **🚦 Ethics Gauge**

The ethics score is visualized using a colored gauge:

- 🟢 **85-100:** Excellent Ethics Compliance  
- 🟡 **70-85:** Moderate Compliance  
- 🔴 **Below 70:** Needs Improvement  

---

## **📜 Policy Compliance Checklist**

| Policy | Status |
|---------|--------|
| Fairness Assessed | ✅ |
| Explainability Verified | ✅ |
| Sensitive Attributes Monitored | ✅ |
| User Consent & Data Validation | ✅ |
| Reproducibility (Colab + Git) | ✅ |

---

## **📈 Example Output**

- SHAP Summary Plot  
- Fairness Metrics Table  
- Ethics Score Gauge Chart  

---

## **📂 Project Structure**

```
ConscienceAI.ipynb   # Main notebook
README.md             # Project documentation
```

---

## **🛡️ License**

This project is licensed under the **MIT License**.

---

## **🤝 Contributing**

Contributions are welcome! Feel free to fork the repo, submit pull requests, or open issues.

---

## **💬 Contact**

For questions or collaboration:

**Lakshya Verma**  
Lakshya.123607@stu.upes.ac.in
