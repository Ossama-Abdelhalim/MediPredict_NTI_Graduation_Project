# 🏥 MediPredict - NTI Graduation Project

**MediPredict** is an end-to-end healthcare data analytics and predictive modeling project developed as part of the NTI (National Telecommunication Institute) Graduation Project. It leverages machine learning algorithms to analyze clinical hospital datasets, forecast medical predictions, and visualize key health metrics through interactive PowerBI dashboards.

---

## 📌 Project Overview

- **Machine Learning Analysis:** Complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and hyperparameter tuning in `MediPredict_last.ipynb`.
- **Model Architecture:** Visualized model pipeline workflow in `How Model Work.png`.
- **Interactive Dashboard:** Executive analytics dashboard built in Microsoft PowerBI (`FinalProject - NTI.pbix`).
- **Scalable Pipeline:** Designed to handle large-scale hospital datasets (~1 Million+ records).

---

## 📁 Repository Structure

```text
MediPredict_NTI_Graduation_Project/
│
├── FinalProject - NTI.pbix      # Interactive PowerBI Dashboard
├── How Model Work.png           # Machine Learning Model Architecture & Flow
├── MediPredict_last.ipynb       # Main Jupyter Notebook (Data Clean, EDA, ML Models)
├── requirements.txt             # Python Dependencies
├── .gitignore                   # Files excluded from version control
└── README.md                    # Project Documentation
```

---

## 🚀 Getting Started

### 1. Prerequisites & Installation

Download the PowerBI File from the drive link in the "PowerBI" text file up

### 2. Dataset Setup

> **Note:** The raw datasets (`MediPredict_Hospital_1_1M_Raw.csv`) and processed datasets (`MediPredict_Cleaned_Data (1).csv`) exceed GitHub's 100MB file limit and are excluded via `.gitignore`.

Place your local copy of the CSV datasets directly into the project root folder before executing the notebook:
- `MediPredict_Hospital_1_1M_Raw.csv`
- `MediPredict_Cleaned_Data (1).csv`

### 3. Running the Machine Learning Notebook

Launch Jupyter Notebook or VS Code to run the modeling pipeline:

```bash
jupyter notebook MediPredict_last.ipynb
```

### 4. Viewing the PowerBI Dashboard

Open `FinalProject - NTI.pbix` using **Microsoft Power BI Desktop** to explore interactive visuals, KPI cards, and data insights.

---

## 📊 Model Workflow

![Model Workflow](How%20Model%20Work.png)

---

## 🛠️ Built With

- **Python 3.10+** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **Microsoft Power BI**
- **Git / GitHub**

---

## 📄 License

This project is created for educational and graduation evaluation purposes under the NTI program.
