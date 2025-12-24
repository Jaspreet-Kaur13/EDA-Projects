# Diabetes Data EDA

This project performs Exploratory Data Analysis (EDA) on a diabetes dataset to uncover patterns, relationships, and insights about the factors affecting diabetes. The goal is to better understand the dataset and prepare it for potential machine learning modeling.
---

## Features

- **Data Loading & Inspection**: Load dataset using Pandas and inspect first few rows.
- **Data Cleaning**: Handle missing/zero values and check for duplicates.
- **Statistical Summary**: Generate mean, median, mode, std deviation, and correlations.
- **Data Visualization**: Histograms, boxplots, heatmaps, scatterplots, countplots.
- **Outlier Detection**: Identify the outliers.
- **Feature Analysis**: Analyze feature relationships with the target variable `Outcome`.

---

## Dataset Description

- **Source**: Kaggle   
- **File**: `diabetes.csv`   

| Column Name      | Description |
|-----------------|-------------|
| Pregnancies      | Number of pregnancies |
| Glucose          | Plasma glucose concentration |
| BloodPressure    | Diastolic blood pressure (mm Hg) |
| SkinThickness    | Triceps skin fold thickness (mm) |
| Insulin          | 2-Hour serum insulin (mu U/ml) |
| BMI              | Body mass index |
| DiabetesPedigreeFunction | Diabetes pedigree function |
| Age              | Age of the patient |
| Outcome          | Target variable (0 = non-diabetic, 1 = diabetic) |

---

## Tools & Libraries

- **Python**
- **Jupyter Notebook**
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Jaspreet-Kaur13/EDA-Projects.git
```

2. Navigate to project folder:
```bash
cd Diabetes-EDA
```

3. Open Jupyter Notebook:
```bash
jupyter notebook
```

4. Run the notebook "Diabetes Data EDA.ipynb".
