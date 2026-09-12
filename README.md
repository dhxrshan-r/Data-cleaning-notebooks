# Data Cleaning Notebooks

A collection of Jupyter notebooks for cleaning and validating messy datasets across nine domains:

- Banking
- E-Commerce
- Employee
- Hospital
- Hotel
- Inventory
- Pharmacy
- Student performance
- University attendance

Each folder contains a messy source CSV, a cleaned CSV, and the notebook used to produce the cleaned data. Cleaning steps include whitespace and missing-value standardization, column normalization, type conversion, validation, duplicate handling, and export.

## Setup

Create and activate a Python environment, then install the dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Run a notebook

Open a notebook in VS Code or Jupyter and run it from its own folder. The notebooks use relative filenames for their input and output CSV files.

For example:

```bash
jupyter notebook Banking/Banking.ipynb
```

Run the cells from top to bottom. The cleaned CSV is written beside the notebook.

## Project structure

```text
Banking/
E-Commerce/
Employee/
Hospital/
Hotel/
Inventory/
Pharmacy/
Student performance/
University Dataset/
requirements.txt
```

The `*_Messy_*.csv` files are source examples. The `*_Cleaned_*.csv` files are generated results retained for comparison and review.
