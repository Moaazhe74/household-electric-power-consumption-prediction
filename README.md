# Household Electric Power Consumption Prediction — Regression Project

## Overview

This project predicts household electric power consumption using historical electrical measurement data.

## Problem Statement

Energy consumption prediction can help understand usage patterns and support better monitoring. This project uses regression models to estimate power consumption from historical measurements.

## Project Workflow

- Loaded and cleaned household electric power consumption data
- Handled missing values and numerical features
- Analyzed electrical measurements such as global active power, global reactive power, voltage, global intensity, and sub-metering features
- Trained regression models to estimate power consumption
- Compared models using standard regression metrics

## Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Technologies & Skills

Python, Pandas, NumPy, Scikit-learn, Regression, Data Analysis, Model Evaluation

## Repository Structure

```text
.
├── data/
│   └── .gitkeep
├── notebooks/
│   └── project_notebook.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/Moaazhe74/household-electric-power-consumption-prediction.git
```

2. Install the required libraries:
```bash
pip install -r requirements.txt
```

3. Open the notebook:
```bash
jupyter notebook notebooks/project_notebook.ipynb
```

## Notes

The dataset is not included if it is large or restricted. If needed, add the dataset source link here.

## Author

**Moaaz Hisham**  
Aspiring Data Scientist | Mathematics & Computer Science Graduate  
LinkedIn: https://www.linkedin.com/in/moaazhisham74/
