
# datafun-02-automation

## Project Overview

This project is a Python automation/data analysis environment. It uses a virtual environment for dependency management and includes a sample `requirements.txt` with common data, analysis, and automation packages.

## Getting Started

### 1. Clone the Repository
```powershell
git clone <repo-url>
cd datafun-02-automation
```

### 2. Create and Activate a Virtual Environment
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
You should see `(.venv)` in your terminal prompt when activated.

### 3. Install Dependencies
Edit `requirements.txt` as needed, then install:
```powershell
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirements.txt
```

## requirements.txt

The `requirements.txt` file contains detailed instructions and a curated list of packages for:
- Data analysis (numpy, pandas, polars)
- Visualization (matplotlib, seaborn)
- Jupyter notebooks (jupyter, ipython, ipykernel, ipywidgets)
- Excel file support (openpyxl, xlsxwriter, xlrd)
- Databases (sqlite3, duckdb, sqlalchemy)
- Machine learning (scikit-learn, statsmodels)
- NLP (nltk, spacy)
- API development (fastapi, uvicorn, pydantic)
- And more

Uncomment or add packages as needed for your project.

## Tips
- Always activate your virtual environment before working on the project.
- Use VS Code's Python extension and select the `.venv` interpreter for best results.
- For Jupyter notebooks, select the `.venv` kernel.


