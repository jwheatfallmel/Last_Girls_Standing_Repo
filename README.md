# Last Girls Standing: Evaluating Harm and Educational Opportunity in Alternative Schooling for Black Girls

## Overview
This repository contains analysis of the 2017-18 Civil Rights Data Collection (CRDC) education data, examining how school-provided opportunities and climate conditions shape student outcomes for Black girls in alternative schools. The analysis employs multiple machine learning classification models including Logistic Regression, Decision Trees, Random Forest, K-Nearest Neighbors, Support Vector Machines (SVM), and XGBoost. Advanced techniques such as SMOTE for handling class imbalance, PCA for dimensionality reduction, and GridSearchCV for hyperparameter optimization are utilized to predict student outcomes.

## Project Structure
```
.
├── 2017-18_CRDC_data/          # Raw CRDC and EDFacts data files
│   └── 2017-18 Public-Use Files/
│       ├── Data/               # CSV data files for LEA and SCH levels
│       └── Documentation/      # Data documentation and file structure
├── figures/                    # Generated visualizations and plots
├── model_data/                 # Cleaned and processed data for modeling
│   ├── feature_df_cleaned.csv
│   └── target_df_cleaned.csv
├── reports/                    # Project reports and documentation
│   ├── LGS_Final_Paper.pdf     # Final Paper of Findings (View my research progress through all of 4 stages)
│   ├── Wheatfall-Melvin_Stage1.pdf
│   ├── Wheatfall-Melvin_Stage2.pdf
│   ├── Wheatfall-Melvin_Stage3.pdf
│   └── Wheatfall-Melvin_Stage4.pdf
└── working_code/               # Jupyter notebook for all code 
```

## Data Description
The project uses 2017-18 CRDC public-use files, which include:
- **LEA (Local Education Agency) Level Data**: District-level education metrics
- **SCH (School) Level Data**: School-level data on enrollment, courses, discipline, and more
- **EDFacts Data**: Supplementary federal education data including Title I status and special education metrics

## Getting Started

### Prerequisites
- Python 3.x
- Required packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - plotnine
  - scikit-learn
  - imbalanced-learn
  - xgboost

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd Last_Girls_Standing_Repo

# Install dependencies
pip install pandas numpy matplotlib seaborn plotnine scikit-learn imbalanced-learn xgboost
```

### Usage 
1. Do

## Authors
Joya Wheatfall-Melvin

## Acknowledgments
This research received support during the PPOL 5204: Data Science II course, instructed by Professor Ioannis Ziogas, PhD at the Georgetown University McCourt School of Public Policy.

Data source: U.S. Department of Education, Office for Civil Rights 
