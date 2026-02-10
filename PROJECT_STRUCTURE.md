# Project Structure

This document outlines the directory structure and module organization of the CV Parsing and Scoring project.

## Directory Structure

```
CV-Parsing-et-Scoring/
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
├── notebooks/
├── src/
│   ├── __init__.py
│   ├── data_processing.py
│   ├── model_training.py
│   └── evaluation.py
├── tests/
│   ├── test_data_processing.py
│   └── test_model_training.py
├── requirements.txt
├── README.md
└── PROJECT_STRUCTURE.md
```

## Module Organization

- **data/**: Contains various datasets used in the project.
  - **raw/**: Raw data that has not been processed.
  - **processed/**: Cleaned and processed data ready for analysis.
  - **external/**: Data obtained from external sources.

- **notebooks/**: Jupyter notebooks for exploratory data analysis and visualization.

- **src/**: Source code for the project.
  - **data_processing.py**: Module for data cleaning and preprocessing tasks.
  - **model_training.py**: Module for training machine learning models.
  - **evaluation.py**: Module for evaluating model performance.

- **tests/**: Unit tests for the project modules.

- **requirements.txt**: List of Python packages required to run the project.

- **README.md**: Overview of the project and setup instructions.
