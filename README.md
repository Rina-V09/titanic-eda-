🛳 Titanic EDA
📌 Overview
This project performs Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover patterns, trends, and relationships influencing passenger survival.
Using Python, the dataset is cleaned, analyzed, and visualized to derive meaningful insights, with results summarized in a detailed PDF report.

📂 Repository Structure
plaintext
Copy
Edit
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
🛠 Tools & Libraries
Python – core programming language

Pandas – data manipulation & preprocessing

NumPy – numerical operations

Matplotlib – static visualizations

Seaborn – statistical visualizations

Jupyter Notebook – analysis & documentation

📊 Analysis Workflow
1️⃣ Data Loading & Overview

Loaded train/test datasets

Used .info(), .describe(), .head() for initial inspection

2️⃣ Data Cleaning

Filled missing values (Age, Embarked, Fare)

Created new features: FamilySize, IsAlone

3️⃣ Exploratory Data Analysis

Examined survival distribution by Sex, Pclass, Age, Fare

Studied feature correlations using a heatmap

4️⃣ Visualization

Histograms & bar charts

Boxplots

Heatmaps

5️⃣ Key Findings

Females had higher survival rates than males

First-class passengers had better chances of survival

Children had higher survival rates compared to adults

Higher fares correlated positively with survival

Traveling alone lowered survival chances

📈 Example Visualizations



📄 Report
A detailed PDF report summarizing the findings is available here:
📁 reports/titanic_eda_report.pdf

🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/titanic-eda.git
cd titanic-eda
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook

bash
Copy
Edit
jupyter notebook notebooks/titanic_eda.ipynb
📬 Author
Rina Kumari
📧 Email: rinavadera2003@gmail.com
🔗 LinkedIn: Rina Kumari

