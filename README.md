# ML — Machine Learning Assignments

Twelve Jupyter notebook assignments, fully executed with outputs embedded.

**Name:** Shreyas Sovani | **Roll No:** 22 | **Class:** AIML-F | **Subject:** Machine Learning

## Structure

```
ML/
├── ASSIGNMENTS/
│   ├── Assignment 1 - Linear Regression/          # advertising.csv  (multiple + simple LR)
│   ├── Assignment 2 - Logistic Regression/        # titanic.csv     (survival prediction)
│   ├── Assignment 3 - KNN/                        # Iris + Diabetes (classification & regression)
│   ├── Assignment 4 - Naive Bayes/                # Breast Cancer   (Gaussian/Multinomial/Bernoulli)
│   ├── Assignment 5 - SVM/                        # Iris + Diabetes (SVC kernels + SVR + GridSearch)
│   ├── Assignment 6 - Decision Tree/              # Breast Cancer + Diabetes (tree viz, overfitting)
│   ├── Assignment 7 - Random Forest/              # Breast Cancer + Diabetes (vs single trees)
│   ├── Assignment 8 - PCA/                        # Wine + Digits   (covariance eigen-decomposition, compression)
│   ├── Assignment 9 - K-Means Clustering/         # Blobs + Iris    (Lloyd's, K-Means++, elbow, silhouette)
│   ├── Assignment 10 - Hierarchical Clustering/   # Shapes + Wine   (linkages, dendrogram cuts, cophenetic)
│   ├── Assignment 11 - Rule-Based Classification/ # Play Tennis + Breast Cancer (FOIL, sequential covering)
│   └── Assignment 12 - Markov Models/             # Weather chain + PageRank (Chapman-Kolmogorov, stationary)
├── requirements.txt
├── .env                                           # Kaggle API token
└── venv/                                          # local virtual environment
```

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
source venv/bin/activate
jupyter lab          # or: jupyter notebook
```

Each notebook is self-contained — datasets sit in the same folder (Assignments 1–2),
load from scikit-learn (Assignments 3–11), or are defined/simulated in the notebook
itself (toy tables in 10–11, Markov chains in 12). All cells already executed; re-run
top-to-bottom to reproduce.

## Export to PDF

In Jupyter: **File → Save and Export Notebook As → PDF**.
