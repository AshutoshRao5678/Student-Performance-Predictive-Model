# Student Performance Predictive Model

## Project Overview
This project predicts student performance in mathematics using machine learning. It includes **Random Forest** and **Decision Tree** models for:

- **Regression**: Predicting math scores
- **Classification**: Predicting pass/fail status

Feature importance analysis is also included to understand which factors most influence performance.

---

## Dataset
- **Source**: [Students Performance in Exams — Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)  
- **Description**: Contains 1000 student records with the following columns:
  - `gender`
  - `race/ethnicity`
  - `parental level of education`
  - `lunch`
  - `test preparation course`
  - `math score`, `reading score`, `writing score`

---

## Repository Structure
Student-Performance-Predictive-Model/
│
├── predictivemodelling.ipynb # Jupyter Notebook with all code, plots, and metrics
├── StudentsPerformance.csv # Dataset
├── outputs/
│ ├── output_0_1.png # Notebook plots
│ └── output_0_2.png
├── predictivemodelling.html # Optional HTML export
├── predictivemodelling.tex # Optional LaTeX export
├── README.md # This file
└── LICENSE (optional) # All Rights Reserved or chosen license

---

## How to Use
1. Open `predictivemodelling.ipynb` in **Jupyter Notebook**.  
2. Run all cells to:
   - Train regression and classification models
   - View evaluation metrics and plots
   - Save trained models and feature columns  
3. Load the saved models (`.pkl`) for future predictions without retraining.

---

## Key Features
- Predicts math score and pass/fail status
- Visualizes **Predicted vs Actual scores**
- Displays **feature importance**
- Models saved for easy reuse
- Fully reproducible and stable

---

## Author
**Ashutosh Rao**  
Project – Predictive Modeling
