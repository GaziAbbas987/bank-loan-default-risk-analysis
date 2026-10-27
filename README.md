# Bank Loan Default Risk Analysis

A beginner-friendly Python project demonstrating exploratory data analysis (EDA) and a baseline machine-learning model for loan-default risk.

> **Important:** The included `loan_default_sample.csv` is synthetic teaching data, not real customer or bank data. Model results are for demonstration only and must not be used for real lending decisions.

## Files
- `bank_loan_default_risk_analysis.ipynb` — main notebook
- `loan_default_sample.csv` — sample dataset (1,200 synthetic records)
- `requirements.txt` — Python dependencies

## Run online with Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Choose **File → Upload notebook** and upload `bank_loan_default_risk_analysis.ipynb`.
3. Upload `loan_default_sample.csv` to the Colab session using the folder icon, or run the notebook without it; the notebook has a fallback generator.
4. Choose **Runtime → Run all**.
5. Review the EDA charts, evaluation metrics, confusion matrix, and example prediction.

## Run locally
Install Python 3.10+ and then run:

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `bank_loan_default_risk_analysis.ipynb` and run all cells.

## Project workflow
1. Load and inspect data
2. Check missing values and duplicates
3. Explore distributions and default patterns
4. Split data into train and test sets
5. Preprocess numerical and categorical features
6. Train logistic regression baseline
7. Evaluate accuracy, precision, recall, F1 and ROC-AUC
8. Demonstrate an example prediction

## Tools
Python, Pandas, NumPy, Matplotlib, scikit-learn, Jupyter Notebook.

## Limitations
The data is synthetic and the model is educational only. Real credit-risk use requires suitable authorized data, validation, bias/fairness review, model governance and expert oversight.

## Author
Gazi Abbas Rizvi
