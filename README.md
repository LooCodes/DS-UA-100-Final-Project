# International Soccer Match Outcome Predictor

## Project Question
Can we predict the outcome of international soccer matches based on team performance metrics such as recent win rate, goal statistics, and FIFA rankings?

As an extension, we aim to use the model to simulate potential matchups in the upcoming World Cup.

## Datasets
We plan to use:

1. International match results dataset  
   Source: https://github.com/martj42/international_results/blob/master/results.csv

2. FIFA world rankings 2026

## Required Project Elements
- Data description and cleaning
- Statistical test
- Variable relationship using correlation
- Causal interpretation
- Predictive model with train/test split
- Data visualization

## Setup Instructions

### 1. Clone the repository

```bash
git clone <your-repo-url>
```

### 2. Create a virtual environment

#### Windows

```bash
python -m venv venv
```

#### Mac / Linux

```bash
python3 -m venv venv
```

### 3. Activate the virtual environment

#### Windows PowerShell

```bash
venv\Scripts\Activate
```


#### Mac / Linux

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run Jupyter Notebook

```bash
jupyter notebook
```

### 6. Deactivate the virtual environment

```bash
deactivate
```

## Project Structure

```text
data/
  raw/          Original datasets
  processed/    Cleaned datasets

notebooks/      Data cleaning, EDA, statistics, and modeling notebooks

src/            Reusable Python scripts/functions

outputs/
  figures/      Saved graphs
  models/       Saved trained models
  results/      Model metrics and other output files
```

## Notes

Make sure `venv/` is listed in `.gitignore` so the virtual environment is not pushed to GitHub.

```bash
venv/
```