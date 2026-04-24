# 🛒 Online Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📋 Overview
This project focuses on analyzing customer behavior in an online shopping environment. By leveraging data science techniques, we explore patterns, detect anomalies, and prepare the data for predictive modeling or deeper business insights.

The analysis covers the entire pipeline from **Data Understanding** to **Advanced Data Cleaning** and **Exploratory Data Analysis (EDA)**.

## 🚀 Key Features
- **Data Preprocessing**: Handling missing values using median/mode imputation.
- **Type Optimization**: Converting data types for efficient processing.
- **Categorical Standardization**: Fixing inconsistencies in naming (e.g., Device types, Gender).
- **Anomaly Detection**: Identifying and treating logical errors (e.g., negative time spent on site).
- **Exploratory Analysis**: Visualizing customer trends and purchase patterns.

## 📂 Project Structure
```text
├── data/                       # Raw and cleaned datasets
│   ├── online_shopping.csv     # Original dataset
│   └── online_shopping_cleaned.csv
├── notebooks/                  # Jupyter notebooks for analysis
│   └── analysis.ipynb          # Main analysis notebook
├── .gitignore                  # Git ignore rules
├── requirements.txt            # Project dependencies
└── README.md                   # Project documentation
```

## 🛠️ Installation & Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/janajawabreh267/Data_Science_Project.git
   ```
2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 📊 Dataset Information
The dataset contains information about customers' sessions, including:
- **Age & Gender**: Demographic details.
- **Time on Site**: Duration of the session.
- **Pages Viewed**: Number of pages visited.
- **Device**: Device used for shopping (Mobile/Desktop).
- **Purchase Amount**: Total spend.
- **Discount Used**: Whether a coupon was applied.
- **Return Customer**: Customer loyalty status.

---
*Developed as part of a Data Science Project.*
