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

## Features

- Loads a dataset (Iris dataset with a synthetic categorical feature for demonstration).  
- Identifies numeric and categorical columns automatically.  
- Handles missing values (imputation).  
- Scales numeric data (standardization).  
- Encodes categorical data (one-hot encoding).  
- Splits data into training and testing sets.  
- Saves the transformed datasets and the preprocessing pipeline to disk.

---
## Features

- Loads a dataset (Iris dataset with a synthetic categorical feature for demonstration).  
- Identifies numeric and categorical columns automatically.  
- Handles missing values (imputation).  
- Scales numeric data (standardization).  
- Encodes categorical data (one-hot encoding).  
- Splits data into training and testing sets.  
- Saves the transformed datasets and the preprocessing pipeline to disk.

---

## Getting Started

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
## Output Files

After running, the following files will be generated in the current directory:

- `X_train_processed.npy` : Preprocessed training features.
- `X_test_processed.npy` : Preprocessed test features.
- `y_train.csv` : Training labels.
- `y_test.csv` : Test labels.
- `preprocessing_pipeline.joblib` : Saved scikit-learn pipeline for reuse.

---

## Code Structure

- `etl_pipeline.py` : Main script containing the ETL pipeline logic.
- `README.md` : Project documentation.

---

## Technologies Used

- [pandas](https://pandas.pydata.org/) : Data manipulation.
- [scikit-learn](https://scikit-learn.org/) : Preprocessing, pipelines, train-test splitting.
- [numpy](https://numpy.org/) : Saving transformed arrays.
- [joblib](https://joblib.readthedocs.io/) : Persisting pipeline.

---
## Notes

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

