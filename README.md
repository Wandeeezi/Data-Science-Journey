# Data-Science-Journey

Short description: My learning path — notebooks, datasets, code and notes while I build data skills.

## Structure
- `DataSetSamples/` - original dataset samples
- `CleanedData/` - cleaned datasets produced during projects
- `notebooks/` - Jupyter notebooks (week-by-week)
- `Week_Value/` - Scripts for reusable processing of code i wrote each week
- `Tutorial1` - Basic Introduction to show data

## Projects

### Week 1 — Data Cleaning
- `Week_1/MessyStudentsCleaning.ipynb`: cleaned `messy_students.csv` → `data/processed/messy_students_cleaned.csv`
- Key techniques: `.drop_duplicates()`, `pd.to_numeric(..., errors='coerce')`, `fillna()`, `pd.to_datetime()`

## How to run
1. Clone:
```bash
git clone https://github.com/Wandeeezi/Data-Science-Journey.git
cd Journey_to_Data_Science
