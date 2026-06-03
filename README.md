# Day 10: Exploratory Data Analysis (EDA) & Data Cleaning Assessment

## Objective

The objective of this project is to perform Exploratory Data Analysis (EDA) and Data Cleaning on a raw dataset to prepare it for Machine Learning applications.

## Deliverables

* eda_report.ipynb
* cleaned_dataset.csv

## Dataset Overview

The dataset contains passenger-related information and includes both numerical and categorical features. The data was inspected, cleaned, analyzed, and validated before final export.

## Tasks Performed

### Phase 1: Data Inspection & Structural Diagnosis

* Examined dataset dimensions using `.shape`
* Analyzed column information using `.info()`
* Generated summary statistics using `.describe().T`
* Identified missing values and data type issues

### Phase 2: Data Cleaning

* Removed duplicate records
* Applied type coercion using `pd.to_numeric()`
* Handled missing values using appropriate strategies:

  * Median for Age
  * Mode for Embarked
  * "Unknown" for Cabin
* Validated final data types

### Phase 3: Exploratory Data Analysis

* Histogram Analysis
* KDE Plot Analysis
* Skewness Analysis
* Box Plot Analysis
* Scatter Plot Analysis
* Correlation Matrix
* Correlation Heatmap
* Outlier Detection using IQR

### Phase 4: Machine Learning Readiness

* Verified removal of duplicates
* Verified missing value handling
* Verified correct data types
* Prepared clean dataset for machine learning workflows

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Final Output

The cleaned dataset was generated and prepared for machine learning model development.
