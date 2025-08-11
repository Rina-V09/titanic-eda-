# 🛳 Titanic EDA

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)  
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)  
![License](https://img.shields.io/badge/License-MIT-green.svg)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## 📌 Overview  
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic dataset** to uncover patterns and relationships that influenced passenger survival.  
The analysis covers **data cleaning, feature engineering, and visualization**, and the findings are compiled into a **PDF report**.

---

<details>
<summary>📂 Repository Structure</summary>

```plaintext
titanic-eda/
│
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── gender_submission.csv
│
├── notebooks/
│   └── titanic_eda.ipynb
│
├── images/
│   ├── Age_distribution.png
│   ├── Survival_Count.png
│   ├── Pclass_VS_Survival.png
│   ├── Fare_distribution.png
│   ├── Fare_by_Pclass_and_Survival.png
│   ├── numeric_correlation_heatmap.png
│
├── reports/
│   └── titanic_eda_report.pdf
│
├── README.md
├── requirements.txt
└── .gitignore
```
</details>

---

## 🛠 Tools & Libraries  

- **Python** – core programming language  
- **Pandas** – data manipulation & preprocessing  
- **NumPy** – numerical operations  
- **Matplotlib** – static visualizations  
- **Seaborn** – statistical visualizations  
- **Jupyter Notebook** – analysis environment  

---

<details>
<summary>📊 Analysis Workflow</summary>

### 1️⃣ Data Loading & Overview  
- Loaded train/test datasets  
- Used `.info()`, `.describe()`, `.head()` for inspection  

### 2️⃣ Data Cleaning  
- Filled missing values (**Age**, **Embarked**, **Fare**)  
- Created new features: `FamilySize`, `IsAlone`  

### 3️⃣ Exploratory Data Analysis  
- Survival distribution by **Sex**, **Pclass**, **Age**, **Fare**  
- Feature correlations via heatmap  

### 4️⃣ Visualization  
- Histograms  
- Bar charts  
- Boxplots  
- Heatmaps  

### 5️⃣ Key Findings  
- **Females** had higher survival rates  
- **First-class** passengers had better chances  
- **Children** had higher survival rates  
- Higher fares correlated with survival  
- Traveling alone lowered survival chances  

</details>

---

## 📈 Example Visualizations  

| Heatmap | Survival Count |
|---------|----------------|
| ![Correlation Heatmap](images/numeric_correlation_heatmap.png) | ![Survival Count](images/Survival_Count.png) |

---

## 📄 Report  
📁 **[Titanic EDA Report (PDF)](reports/titanic_eda_report.pdf)**  

---

## 🚀 How to Run  

\`\`\`bash
# 1. Clone the repository
git clone https://github.com/yourusername/titanic-eda.git
cd titanic-eda

# 2. Install dependencies
pip install -r requirements.txt

# 3. Open the Jupyter Notebook
jupyter notebook notebooks/titanic_eda.ipynb
\`\`\`

---

## 📬 Author  
**Rina Kumari**  
📧 [rinavadera2003@gmail.com](mailto:rinavadera2003@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/rina-508462249/)  
