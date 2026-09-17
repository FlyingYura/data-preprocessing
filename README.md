# Data Preprocessing — Asthma Patients

Feature preparation for the asthma diagnosis ML pipeline. Reads cleaned clinic data from PostgreSQL and produces a model-ready table.

## What this project covers

- Missing-value analysis and imputation strategy
- Encoding: **Label Encoding** (binary) and **One-Hot** (nominal, `drop_first=True`)
- Outlier handling on numeric features
- Feature scaling with **StandardScaler**
- Writing the processed dataset back to the database

## Stack

`Python` · `pandas` · `numpy` · `scikit-learn` · `SQLAlchemy` · `PostgreSQL`