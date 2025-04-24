Overview
This repository contains my approach to the Kaggle "Predict Loan Default" competition, focusing on building a predictive model using tidyverse and tidymodels frameworks. The project includes comprehensive exploratory data analysis (EDA) with ggplot2 and corrplot, feature engineering, and a random forest model implementation.

Features
Tidyverse Workflow: Clean data manipulation using dplyr and tidyr

Visual EDA:

ggplot2 for insightful visualizations

corrplot for correlation matrix visualization

Modeling Framework:

tidymodels for consistent modeling interface

Random forest implementation with ranger engine

Model tuning and evaluation

Reproducible Research: Complete documentation of the analytical process

Project Structure
├── data/                 # Processed datasets
├── notebooks/            # Analysis notebooks
│   ├── 01_eda.Rmd        # Exploratory Data Analysis
│   ├── 02_preprocessing.Rmd  # Feature engineering
│   └── 03_modeling.Rmd   # Model development
├── R/                    # Utility functions
├── reports/              # Generated reports
└── README.md             # Project overview
Key Findings
Identified key predictors of loan default through EDA

Engineered relevant features to improve model performance

Developed a random forest model with competitive performance

Requirements
R (≥ 4.0.0)

tidyverse

tidymodels

ggplot2

corrplot

ranger (for random forest implementation)
