# CSV Analytics Practice

Notebooks for practising the first hour with a new, messy dataset: inspecting it, cleaning it, and querying it with SQL. Both datasets are synthetic fintech data with deliberate quality problems, such as mixed ID formats, inconsistent city names, invalid tenors and non-boolean flags.

| File | What it covers |
|---|---|
| `Data_Inspection_Template.ipynb` | A reusable step-by-step checklist (shape, dtypes, nulls, duplicates, sanity checks, cleaning), worked through on `transactions_dataset.csv` |
| `analysis.ipynb` | Finding and fixing anomalies in `loans_dataset.csv` |
| `SQL_Practice_Loans.ipynb` | The same loans data loaded into in-memory SQLite and analysed with SQL |
| `analysis_basics.txt` | A short pandas cheat sheet |

## Run

```bash
python -m venv .venv && source .venv/bin/activate
pip install pandas numpy matplotlib jupyter
jupyter notebook
```
