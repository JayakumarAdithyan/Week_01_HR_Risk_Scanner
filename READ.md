# Employee Attrition Risk Scanner (Week 1)

## Business problem
Companies lose money when employees leave. This tool flags employees who may be at risk of leaving.

## Dataset
Hugging Face: BrotherTony/employee-burnout-turnover-prediction-800k
Synthetic data, CC-BY-NC-ND 4.0. Used for learning only.

## How it works
Each employee is a dictionary. Three rules add points: low satisfaction, high overtime, low career progression. The total score becomes LOW, MEDIUM, HIGH or CRITICAL.

## Results (1000 employees)
- LOW: 599 employees, 23.0% left
- MEDIUM: 363 employees, 28.9% left
- HIGH: 14 employees, 50.0% left
- CRITICAL: 24 employees, 37.5% left

Higher-risk groups left more often than LOW, but HIGH and CRITICAL have small samples, so the numbers are only a rough guide.

## Limitations
Educational rule-based scanner. Not machine learning, and not a real employee decision system. The data is synthetic.

## What I learned
Dictionaries, lists, loops, functions and try/except. Next: NumPy and Pandas.
