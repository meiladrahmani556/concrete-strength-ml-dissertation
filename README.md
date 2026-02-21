# Dissertation – Engineering Machine Learning

## 1. Project Overview

This repository contains the MSc dissertation project focused on the application of
**numerical machine learning techniques to engineering problems**.

The aim of the project is to design, implement, and evaluate machine learning models
for predicting engineering system performance using structured numerical data.
The work follows a clear, reproducible, and academically sound workflow implemented
using Python and Jupyter Notebooks.

---

## 2. Project Aim and Objectives

### Aim
To develop and evaluate numerical machine learning models for predicting
**concrete compressive strength** based on mix composition and curing parameters.

### Objectives
- Select and justify an engineering-focused numerical dataset
- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Train baseline and advanced regression models
- Evaluate model performance using appropriate metrics
- Interpret results in an engineering context

---

## 3. Dataset Shortlist (Engineering-Focused)

In preparation for supervisor review, the following **five engineering-related datasets**
were shortlisted. These datasets avoid widely used demonstration datasets and are
relevant to real-world engineering applications.

1. **Concrete Compressive Strength Dataset**  
   - Engineering domain: Civil / Structural Engineering  
   - Task: Regression  
   - Description: Predicting concrete compressive strength from mix design parameters  

2. **Airfoil Self-Noise Dataset**  
   - Engineering domain: Mechanical / Aerodynamics  
   - Task: Regression  
   - Description: Predicting airfoil noise levels from aerodynamic variables  

3. **Steel Plate Faults Dataset**  
   - Engineering domain: Manufacturing / Materials Engineering  
   - Task: Classification  
   - Description: Classification of surface defects in steel plates  

4. **Hydraulic System Condition Monitoring Dataset**  
   - Engineering domain: Mechanical / Mechatronics Engineering  
   - Task: Classification  
   - Description: Fault diagnosis using sensor measurements  

5. **Turbofan Engine Degradation (NASA CMAPSS)**  
   - Engineering domain: Aerospace / Mechanical Engineering  
   - Task: Regression  
   - Description: Remaining useful life prediction using engine sensor data  

---

## 4. Selected Dataset

The **Concrete Compressive Strength Dataset** has been selected for this project due to:
- Its strong engineering relevance
- Fully numerical structure
- Moderate size and clean feature set
- Clear physical interpretation of input variables

### Dataset Details
- Source: UCI Machine Learning Repository  
- Data type: Numerical (tabular)  
- Task: Regression  
- Target variable: Concrete compressive strength (MPa)

---

## 5. Repository Structure

The repository is organised as follows:

- `notebooks/` – Jupyter notebooks implementing each stage of the project  
- `data/` – Raw and processed datasets (excluded from version control where required)  
- `README.md` – Project documentation  

Notebooks are numbered to reflect the logical execution order.

---

## 6. Project Workflow and Notebooks

| Notebook | Description | Status |
|--------|------------|--------|
| 01 | Project plan and dataset overview | Completed |
| 02 | Dataset loading and inspection | Pending |
| 03 | Data cleaning and preprocessing | Pending |
| 04 | Exploratory data analysis (EDA) | Pending |
| 05 | Baseline regression models | Pending |
| 06 | Advanced models and comparison | Pending |
| 07 | Results discussion and conclusions | Pending |

---

## 7. Tools and Libraries

The project is implemented using the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

All notebooks are designed to be executable in **Google Colab**.

---

## 8. Project Status

- New repository initialised
- Project plan defined
- Engineering-focused dataset shortlist prepared
- Final dataset selected
- Ready to proceed with dataset loading and analysis
