# Expense Tracker

This folder contains an expense tracking project built as a Jupyter Notebook. It loads expense data from `expenses.csv` and performs exploratory data analysis, summary statistics, and basic visualizations to help understand spending patterns.

## Contents

- `main.ipynb` - The main Jupyter Notebook for the expense tracker analysis.
- `expenses.csv` - Sample expense data used by the notebook.
- `requirements.txt` - A placeholder for Python dependencies.

## Features

- Loads expense data from a CSV file
- Displays data structure, summary statistics, and missing values
- Analyzes categories and payment methods
- Plots expense totals by category and payment type
- Shows daily and monthly expense trends
- Computes a 7-day moving average of expense totals

## Setup

1. Install Python 3.8+.
2. Create and activate a virtual environment (recommended):

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS / Linux
source venv/bin/activate
```

3. Install required packages:

```bash
pip install pandas matplotlib seaborn notebook
```

4. Launch Jupyter Notebook from this folder:

```bash
jupyter notebook
```

5. Open `Expense_Tracker/main.ipynb` in your browser.

## Usage

- Run the notebook cells sequentially to load and analyze the expense data.
- Modify `expenses.csv` with your own expense records and rerun the notebook.
- Add additional plots or summaries to extend the analysis.

## Notes

- Ensure `expenses.csv` is located in the same folder as `main.ipynb`.
- The notebook expects a `date`, `amount`, `category`, and `payment_method` column structure.

## License

This project is provided as-is for educational purposes.
