# Machine Learning Practice

A collection of Jupyter notebooks built while practicing data manipulation, visualization, preprocessing, and classification modeling with pandas and scikit-learn — largely developed alongside the IIT Madras BS Data Science program (MLT/MLP coursework).

## Structure

```
Machine-Learning-Practice/
├── data-manipulation/   # pandas fundamentals: loading, merging, concatenation,
│                         # apply/map, pivot tables, comparisons
├── visualization/        # Matplotlib and Seaborn plotting practice
├── preprocessing/        # Missing value imputation (incl. KNN imputer),
│                         # preprocessing pipelines
├── models/                # Classification model building — logistic regression,
│                         # perceptron, SVM, and OPPE (graded exam) practice notebooks
└── data/                  # Supporting CSV datasets used across notebooks
```

## Topics covered

- **Data manipulation** — loading, merging, concatenating, and reshaping DataFrames; applying functions with `map`/`apply`; pivot tables
- **Visualization** — Matplotlib and Seaborn for exploratory data analysis
- **Preprocessing** — handling missing data (including KNN-based imputation), preparing features for modeling
- **Modeling** — building and comparing classifiers: Logistic Regression, Perceptron, SVM, and end-to-end pipeline practice for OPPE-style exams

## Notes

Notebooks are self-contained practice exercises rather than a single unified project, reflecting iterative coursework progress. CSV files in `data/` are referenced by notebooks in `preprocessing/` and `models/`.
