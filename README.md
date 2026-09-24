<div align="center">

# Pandas for Data Analysis

### Practical data analysis workflows with Pandas Series and DataFrames

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**A structured, notebook-first repository for learning and practicing real-world data manipulation with Pandas.**

</div>

---

## Overview

This repository contains hands-on Jupyter notebooks and sample datasets for working with tabular data in Python. The material progresses from Pandas Series fundamentals to DataFrame selection, transformation, aggregation, combining, and time-based analysis.

It is intended for Python learners building practical data analysis skills. Examples use CSV and Excel datasets to demonstrate common data workflows.

## Learning path

### 01 · Pandas Series

The Series notebooks cover:

- Creating a Series from lists
- Series attributes
- Reading CSV data
- Series methods and indexing
- Built-in Python functionality with Series
- Plotting Series data

### 02 · Pandas DataFrames

The DataFrame notebooks cover:

- DataFrame attributes and methods
- Selecting rows and columns
- Filtering records
- Applying functions
- Grouping and aggregation
- Merging, joining, and concatenating DataFrames
- MultiIndex operations
- Vectorized string operations
- Date and time data

### 03 · Practice

`practice.py` contains additional Python practice alongside the notebook-based material.

## Repository structure

```text
pandas-data-analysis/
├── 01_Pandas_Series/
│   ├── Data_Sets/
│   ├── 01_Series_from_list.ipynb
│   ├── 02_Series_Attributes.ipynb
│   ├── 03_Series_Using_read_CSV.ipynb
│   ├── 04_Series_Methods.ipynb
│   ├── 05_Series_Indexing.ipynb
│   ├── 06_Series_with_python_Functionalities.ipynb
│   └── 07_Series_plotting.ipynb
├── 02_Pandas_DataFrame/
│   ├── Data_Sets/
│   ├── datasets-session-21/
│   ├── datasets-session-22/
│   ├── 01_Attributes&Methods.ipynb
│   ├── 02_Selecting_Col&Row_From_DataFrame.ipynb
│   ├── 03_Filtering_a_DataFrame.ipynb
│   ├── 04_Functions.ipynb
│   ├── 05_GroupbyObject.ipynb
│   ├── 06_mergingJoining&concatenating.ipynb
│   ├── 07_multiindex.ipynb
│   ├── 08_Vectorized_String.ipynb
│   └── 09_Date&Time.ipynb
└── practice.py
```

## Getting started

### Requirements

- Python 3.9 or later
- JupyterLab or Jupyter Notebook
- Pandas, Matplotlib, and an Excel reader for `.xlsx` files

### Install

Create and activate a virtual environment, then install the core packages:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
python -m pip install pandas jupyterlab matplotlib openpyxl
```

macOS or Linux:

```bash
source .venv/bin/activate
python -m pip install pandas jupyterlab matplotlib openpyxl
```

### Launch the notebooks

From the repository root, start JupyterLab:

```bash
jupyter lab
```

Open a notebook from `01_Pandas_Series` or `02_Pandas_DataFrame` and run its cells in order. Some notebooks expect their sample data to remain in the repository's `Data_Sets` or session-specific dataset folders; preserve the directory structure when moving or uploading files.

## Working with the datasets

Sample data is organized alongside the notebooks. Before redistributing any dataset, check its source and terms of use. The repository's MIT license applies to original project code and documentation; third-party datasets may have separate licenses or restrictions.

Avoid committing private, confidential, or personally identifiable data.

## Suggested workflow

1. Start with the Series notebooks, then continue to DataFrames.
2. Run each notebook from top to bottom and inspect the outputs.
3. Change filters, column names, and aggregation functions to explore the results.
4. Keep dataset paths relative to the repository so notebooks work across machines.

## Contributing

Contributions that improve accuracy, readability, or reproducibility are welcome. Keep each notebook focused on a topic, explain non-obvious transformations, and use clear, consistent filenames.

## License

This project is licensed under the [MIT License](LICENSE). The license applies to original code and documentation in this repository. Third-party datasets and other included materials remain subject to their respective terms.

---

<div align="center">
  <sub>Learn by exploring, transforming, and understanding data.</sub>
</div>

