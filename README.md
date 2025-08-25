# Financial Delinquency Predictor - Tata Internship

This repository contains a credit risk modeling project titled **"Early Risk Indicators for Predicting Delinquency"**. The project was developed as part of a Tata internship, and aims to identify early signals of financial delinquency using a synthetic or anonymized dataset.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
- [Notebooks](#notebooks)
- [Analysis Highlights](#analysis-highlights)
- [Requirements](#requirements)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Credit risk modeling is essential for financial institutions to detect potential delinquencies and mitigate risk. This project explores various early indicators of delinquency using statistical analysis and machine learning models.

**Key Goals:**
- Identify variables most predictive of customer delinquency.
- Visualize relationships between risk indicators and delinquency status.
- Build and evaluate simple predictive models.

## Features

- Data exploration and cleaning (handling missing values, identifying duplicates)
- Feature selection based on domain knowledge and statistical analysis
- Visualization of relationships between key variables and delinquency
- Correlation analysis
- Basic modeling (Logistic Regression, Decision Tree)
- Model evaluation and interpretation

## Dataset

The dataset used (`Tata_intern.xlsx`) includes the following features for 500 customers:

- Demographics: `Age`, `Income`, `Employment_Status`, `Location`
- Account details: `Account_Tenure`, `Credit_Card_Type`
- Financial variables: `Credit_Score`, `Credit_Utilization`, `Loan_Balance`, `Debt_to_Income_Ratio`
- Repayment behavior: `Missed_Payments`, `Month_1` ... `Month_6`
- Target variable: `Delinquent_Account` (1 for delinquent, 0 otherwise)

> **Note:** The dataset is not provided here for confidentiality reasons. Replace the data loading step with your own data if necessary.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mr-kashi6t8/Financial-Delinquency-Predictor-Tata.git
   cd Financial-Delinquency-Predictor-Tata
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Place the dataset** (`Tata_intern.xlsx`) in the project directory.

4. **Open and run the notebook:**
   - Launch Jupyter Notebook or JupyterLab
   - Open `Tata_internship.ipynb` and run all cells

## Notebooks

- [`Tata_internship.ipynb`](./Tata_internship.ipynb): Main notebook with all data exploration, visualization, and modeling steps.

## Analysis Highlights

- **Early Risk Indicators:**  
  - `Missed_Payments`, `Credit_Utilization`, and `Debt_to_Income_Ratio` are strong predictors of delinquency.
- **Data Cleaning:**  
  - Missing values are imputed using mean values for numerical fields.
  - No duplicate rows in the dataset.
- **Visualization:**  
  - Boxplots and barplots show the relationship between risk factors and account delinquency.
- **Modeling:**  
  - Logistic Regression and Decision Tree models were explored.
  - Model evaluation metrics (accuracy, confusion matrix) are provided.

## Requirements

- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter

Install all dependencies using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Or use the provided `requirements.txt`.

## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repository and submit a pull request.

## License

This project is for educational and demonstration purposes.  
For any commercial or production use, please consult the repository owner.

---

**Author:** [mr-kashi6t8](https://github.com/mr-kashi6t8)
