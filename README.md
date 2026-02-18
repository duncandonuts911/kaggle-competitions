# kaggle-competitions
For learning and practicing with Kaggle competitions and Jupyter notebooks

# intended structure of repository
kaggle-portfolio/
├── .gitignore               # Vital: Ignore large .csv and .zip files
├── requirements.txt         # Common libraries (pandas, scikit-learn, etc.)
├── utils/                   # Shared code used across all competitions
│   ├── plotting.py          # Custom confusion matrices or EDA plots
│   └── validation.py        # Shared K-Fold or Stratified split logic
│
├── competition-name-01/     # Folder for a specific contest
│   ├── data/                # Gitignored! Only keep sample_submission here
│   ├── notebooks/           # The "Lab"
│   │   ├── 01-eda.ipynb
│   │   ├── 02-feature-eng.ipynb
│   │   └── 03-model-v1-xgboost.ipynb
│   ├── src/                 # Refactored scripts for long training runs
│   ├── submissions/         # Track your .csv outputs and their scores
│   └── README.md            # Brief summary of your rank and approach
│
└── competition-name-02/     # Repeat for next project
