# Validation and Screening of Concrete Mixtures for Prescribed Thermal Conductivity under Sparse Experimental Coverage

This repository contains the data and Python scripts supporting the study on composition-aware validation and screening of concrete mixtures for prescribed thermal conductivity under sparse experimental coverage.

## Repository structure

- **S1_Dataset_and_Metadata**  
  Experimental dataset, metadata, composition coverage, and scripts for reproducing the main dataset summaries.

- **S2_GB_Validation_and_Distance**  
  Gradient Boosting validation records, composition-holdout predictions, distance diagnostics, and scripts for reproducing the validation results.

- **S3_Screening_Interpretation_and_Accounting**  
  Screening results, SHAP/ICE interpretation outputs, candidate records, Pareto analysis, accounting sensitivity, and reproduction scripts.

- **S4_Additional_Models_and_Refits**  
  Aggregate Ridge, ExtraTrees, and candidate-refit summaries, with scripts for reproducing the corresponding supplementary tables.

## Running the code

Install the required packages in each supplementary folder and run the corresponding reproduction script. For example:

```bash
pip install -r S1_Dataset_and_Metadata/requirements.txt
python S1_Dataset_and_Metadata/code/reproduce_S1_summary.py
```

Equivalent reproduction scripts are provided for S2–S4.

## Data Availability Statement

The data and code supporting the findings of this study are openly available in this GitHub repository.
