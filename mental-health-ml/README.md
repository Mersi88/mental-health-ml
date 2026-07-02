# Mental Health in Tech - ML Pipeline

A complete end-to-end machine learning project predicting whether tech workers seek mental health treatment based on workplace and demographic factors.

## Project Overview
Built an ETL pipeline and Random Forest classifier using the OSMI Mental Health in Tech Survey dataset (1,259 responses).

## Results
- Model Accuracy: 75%
- Most predictive factor: work_interfere (how much mental health affects work)

## Pipeline
- **Extract**: Load raw survey data
- **Transform**: Clean and encode 23 features
- **Load**: Store cleaned data in SQLite database

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (Random Forest Classifier)
- SQLite (ETL pipeline)
- Matplotlib, Seaborn (visualization)
- Jupyter Notebook

## Key Features
- ETL pipeline with SQLite integration
- Data cleaning (age filtering, gender standardization, missing value handling)
- Feature importance visualization
- Prediction function for new inputs
