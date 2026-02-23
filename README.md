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

The dataset selected for this dissertation is the **Concrete Compressive Strength Dataset**, which has a strong civil and materials engineering context.

- Domain: Civil / Structural Engineering  
- Task: Regression  
- Objective: Predict concrete compressive strength (MPa) based on material composition and curing age  
- Number of samples: 1030  
- Number of features: 8 input variables + 1 target variable  

### Input Features
- Cement (kg/m³)
- Blast Furnace Slag (kg/m³)
- Fly Ash (kg/m³)
- Water (kg/m³)
- Superplasticizer (kg/m³)
- Coarse Aggregate (kg/m³)
- Fine Aggregate (kg/m³)
- Age (days)

### Target Variable
- Concrete Compressive Strength (MPa)

---

## 5. Repository Structure

The repository is organised as follows:

- `notebooks/` – Jupyter notebooks for each project stage  
- `data/` – Concrete compressive strength dataset (CSV format)  
- `README.md` – Project documentation  

---

## 6. Project Workflow and Notebooks/Project Structure 
**Notebook 01 – Problem Definition**
- Defines the engineering problem of predicting concrete compressive strength
- Establishes objectives, scope, and machine learning relevance
- Justifies dataset choice and regression approach

**Notebook 02 – Data Acquisition**  
- Sources the concrete compressive strength dataset
- Explains dataset features and engineering meaning
- Loads and validates raw data for further processing

**Notebook 03 – Data Cleaning & Preprocessing**  
- Handles missing values and duplicates
- Renames columns for consistency and clarity
- Performs basic statistical validation
- Outputs a cleaned dataset for analysis and modelling

**Notebook 04 – Exploratory Data Analysis (EDA)**  
- Analyses feature distributions and ranges
- Investigates relationships between material components
- Identifies correlations with compressive strength
- Supports informed feature selection and model choice

| Notebook | Description | Status |
|--------|------------|--------|
| 01 | Project plan and dataset overview | Completed |
| 02 | Dataset loading and inspection | Completed |
| 03 | Data cleaning and preprocessing | Completed |
| 04 | Exploratory data analysis (EDA) | Completed |
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

- Project scope defined and approved  
- Engineering dataset shortlisted and selected  
- Notebooks 01–03 completed:
  - **Notebook 01:** Project setup and dataset overview  
  - **Notebook 02:** Data loading and initial inspection  
  - **Notebook 03:** Data cleaning and preprocessing  
- Cleaned dataset generated and saved  
- Ready to proceed to exploratory data analysis (Notebook 04)
