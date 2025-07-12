# 🌍 Financial Inclusion in Africa: Predicting Bank Account Ownership

This project aims to predict which individuals in East Africa are most likely to have or use a bank account using machine learning. It also identifies key socio-economic factors affecting financial access in Kenya, Uganda, Rwanda, and Tanzania.

---

## 📌 Project Objective

- Assess financial inclusion in East Africa using survey data
- Build predictive models to identify individuals likely to have a bank account
- Provide actionable insights to guide policy and improve access to financial services

---

## 🧠 Techniques Used

### 🔄 Data Preprocessing
- Removed irrelevant identifiers
- Handled missing values (none found)
- Categorical feature encoding with `LabelEncoder`
- Feature correlation analysis

### 📊 Exploratory Data Analysis
- Visualized relationships between features and bank account ownership
- Country-wise comparison of inclusion rates
- Analysis of education, gender, location type, and age on account ownership

### 🤖 Machine Learning Models
- Logistic Regression
- Random Forest
- Gradient Boosting
- Neural Network (MLPClassifier)

---

## 🧰 Tools & Libraries

- **Languages**: Python
- **Libraries**:
  - Data manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
  - Deep Learning: `keras`, `tensorflow`

---

## 📈 Key Insights

- Urban residents, higher education, and higher household income increase likelihood of having a bank account.
- Rural areas and younger age groups are disproportionately underbanked.
- Among the four countries, Kenya and Rwanda had higher rates of inclusion, while Tanzania had the lowest.

---

## 🧪 Model Performance

| Model                | Accuracy | Precision | Recall | F1-Score |
|----------------------|----------|-----------|--------|----------|
| Logistic Regression  | ~0.85    | Good      | Fair   | Good     |
| Random Forest        | Higher   | High      | High   | High     |
| Gradient Boosting    | Best     | Excellent | Good   | Best     |
| Neural Network (MLP) | Strong   | Good      | Good   | Good     |

*Note: Exact metrics provided in the notebook.*

---

## 📂 File Structure

```
📁 Financial-Inclusion-Africa
│
├── Data Science Project 2.ipynb    # Main notebook
├── README.md                       # Project documentation
```

---

## 📝 Data Source

- [Zindi Africa – Financial Inclusion Challenge](https://zindi.africa/competitions/financial-inclusion-in-africa)

The dataset contains demographic and socio-economic information of individuals in Kenya, Uganda, Rwanda, and Tanzania, including their bank account ownership status.

---

## 🌐 Impact

Improving financial inclusion can:
- Support entrepreneurship
- Reduce poverty and inequality
- Increase household resilience
- Promote economic growth in developing regions

---

## 🚀 Future Work

- Add geospatial analysis to identify regional disparities
- Apply advanced techniques like SHAP for interpretability
- Deploy as a dashboard or mobile tool for NGOs/policymakers

---

## 🤝 Connect with Me

**Taketo Horigome**  
🎓 Data Science | CU Boulder  
🔗 [LinkedIn](https://www.linkedin.com/in/taketo-horigome-29b26532b)  
📧 liverdom@icloud.com

