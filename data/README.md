# Data

This folder contains the datasets used in the project, organized according to their role in the data processing pipeline.

All data used in this project are **synthetic banking data** provided for academic purposes.

---

## Folder Structure

- **processed/**  
  Contains the cleaned and transformed datasets generated during the data preparation phase.  
  These datasets are used to build the final analytical basetable and support exploratory and descriptive analyses.

- **README.md**  
  This file documents the data structure and explains how datasets are organized and used throughout the project.

---

## Data Usage

- Raw input files are read and processed in the Jupyter notebook using **relative paths**
- Data cleaning, feature engineering, and aggregation steps are performed programmatically
- The final basetable is saved in the `processed/` folder and reused for analysis and visualization

This structure ensures reproducibility and makes the project easy to run and understand for external users.

---

## Notes

No sensitive or real customer information is included in this repository.

