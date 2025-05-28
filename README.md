
# Clinical Readmission Prediction & Entity Extraction – Data Science Assessment

## Overview

This project addresses two core tasks for a clinical data science pipeline:

1. **Binary Classification:** Predict whether a patient will be readmitted to hospital within 30 days, 
using structured clinical features.

2. **Named Entity Recognition (NER):** Extract and categorize key medical information
 (diagnosis, treatment, symptom, medication, follow-up action) from free-text discharge notes using NLP/LLM approaches.

## Files

- `Discharge_Prescription.ipynb` – Main Jupyter Notebook with all code, analysis, and results.
- `Assignment_Data.csv` – Provided dataset.
- `Report-Summary-Clinical Data Science.pdf` – Short final report summarizing approach, key results, and practical implications.


## Setup & Installation


Launch Jupyter Notebook:Then open Discharge_Prescription.ipynb in your browser.


## How to Run:

Run all cells in assignment_notebook.ipynb in order.

Make sure Assignment_Data.csv is in the same directory as your notebook.

## The notebook includes:

Exploratory data analysis and feature engineering

Model training, evaluation, and feature importance

Named entity extraction from discharge notes using Hugging Face Transformers and Flan-T5

Discussion of risks, limitations, and recommendations


## Results:

Classification: ROC AUC, F1-score, confusion matrix, and feature importances are displayed in the notebook 
and summarized in Report-Summary-Clinical Data Science.pdf.

NER: Demo outputs for both standard NER and LLM-based approaches.

## Notes:
General-purpose NER and LLMs (like Flan-T5) have limitations on clinical text. 
For production, consider clinical-specific models.

With more data and features, predictive performance is expected to improve.

### Contact:
For questions, please contact vijy_24@yahoo.in
