## Heart-Disease-Analysis
Heart Disease Data Analysis(Python)
Performed Exploratory Data Analysis on a heart disease dataset to identify potential risk factors.Implemented data preproessing, data visualization using NumPy, Matplotlib, and Seaborn.The project demonstrates foundational data analysis skills and practical applications of python in Healthcare related datasets.
The notebook demonstrates real-world clinical data handling, including missing value treatment, statistical summaries, and visual exploration.

## 📊 Dataset Description

- Records: 4,240 patients

- Target Variable: TenYearCHD (0 = No risk, 1 = At risk)

- Source: Public clinical heart disease dataset (Framingham-style data)

## Key Features

- Demographics: age, male, education

- Lifestyle factors: currentSmoker, cigsPerDay

- Medical history: diabetes, prevalentStroke, prevalentHyp, BPMeds

- Clinical measurements: sysBP, diaBP, totChol, BMI, heartRate, glucose

## 🛠️ Tools & Technologies

- Python

- Pandas & NumPy – data handling & numerical analysis

- Matplotlib & Seaborn – data visualization

- Google Colab / Jupyter Notebook

## 🔍 Analysis Workflow

- Data Loading & Inspection

- Checked data structure, datatypes, and column consistency

- Generated statistical summaries using info() and describe()

- Missing Value Handling

- Identified missing values across clinical features

- Applied median imputation to numerical columns to preserve data distribution

- Exploratory Data Analysis

- Target variable distribution (TenYearCHD)

- Age distribution analysis

- Smoking behavior vs cigarette consumption

- Blood pressure impact on heart disease risk

- Feature correlation analysis using heatmaps

- Visualization Insights

- Identified class imbalance in heart disease outcomes

- Observed increased CHD risk with age and elevated systolic BP

- Strong correlations among blood pressure, BMI, and cholesterol variables

## 📈 Key Insights

- Older age groups show higher heart disease risk.

- Elevated systolic blood pressure is strongly associated with CHD.

- Smoking intensity varies significantly between smokers and non-smokers.

- Clinical variables such as BP, BMI, and cholesterol exhibit notable correlations.
