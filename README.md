# Codetech-Task-1

Name:- BISHAL KUMAR SHARMA 
Company:- CODTECH IT SOLUTIONS 
ID:- CT04DG1321
Domain:- DATA SCIENCE 
Duration:- 14th JUNE TO 14th JULY 2025
Mentor:- NEELA SANTOSH KUMAR 


# ETL Pipeline: Data Preprocessing, Transformation & Loading

This repository contains a Python script (`etl_pipeline.py`) that implements an automated ETL (Extract, Transform, Load) pipeline using **pandas** and **scikit-learn**.

It demonstrates a typical data preprocessing flow, including handling numeric & categorical data, scaling, encoding, splitting datasets, and saving the output.

---

## ðŸ“„ Features

âœ… Loads a dataset (Iris dataset with a synthetic categorical feature for demonstration).  
âœ… Identifies numeric and categorical columns automatically.  
âœ… Handles missing values (imputation).  
âœ… Scales numeric data (standardization).  
âœ… Encodes categorical data (one-hot encoding).  
âœ… Splits data into training and testing sets.  
âœ… Saves the transformed datasets and the preprocessing pipeline to disk.

---
## ðŸ“„ Features

âœ… Loads a dataset (Iris dataset with a synthetic categorical feature for demonstration).  
âœ… Identifies numeric and categorical columns automatically.  
âœ… Handles missing values (imputation).  
âœ… Scales numeric data (standardization).  
âœ… Encodes categorical data (one-hot encoding).  
âœ… Splits data into training and testing sets.  
âœ… Saves the transformed datasets and the preprocessing pipeline to disk.

---

## ðŸš€ Getting Started

### Prerequisites

- Python 3.7+
- Install the required libraries:

```bash
pip install pandas scikit-learn numpy joblib
```

### Running the Script

```bash
python etl_pipeline.py
```

---
## ðŸ“ Output Files

After running, the following files will be generated in the current directory:

- `X_train_processed.npy` â€” Preprocessed training features.
- `X_test_processed.npy` â€” Preprocessed test features.
- `y_train.csv` â€” Training labels.
- `y_test.csv` â€” Test labels.
- `preprocessing_pipeline.joblib` â€” Saved scikit-learn pipeline for reuse.

---

## ðŸ“‚ Code Structure

- `etl_pipeline.py` â€” Main script containing the ETL pipeline logic.
- `README.md` â€” Project documentation.

---

## ðŸ“š Technologies Used

- [pandas](https://pandas.pydata.org/) â€” Data manipulation.
- [scikit-learn](https://scikit-learn.org/) â€” Preprocessing, pipelines, train-test splitting.
- [numpy](https://numpy.org/) â€” Saving transformed arrays.
- [joblib](https://joblib.readthedocs.io/) â€” Persisting pipeline.

---
## ðŸ”— Notes

- By default, the script uses the Iris dataset from `sklearn.datasets` and adds a dummy categorical feature (`category`) for demonstration.
- You can modify the script to read your own dataset by replacing the dataset loading section with:
  ```python
  df = pd.read_csv('your_dataset.csv')
  ```

---
## Resources:- 
- Youtube
- Google
- Chatgpt

