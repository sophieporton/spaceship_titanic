# Spaceship Titanic

A data science / machine‑learning project to predict which passengers on
the fictional "Spaceship Titanic" are transported to an alternate
dimension --- based on the public dataset from Kaggle.

## 🚀 Overview

This repository offers a full pipeline for tackling the challenge ---
from exploratory data analysis (EDA), through feature engineering and
preprocessing, to model training and evaluation.

Key components:

-   **Exploratory Data Analysis (EDA)** --- examine dataset structure,
    distributions, correlations, missing values.
-   **Feature Engineering** --- derive new features (e.g. from cabin
    information), clean and encode data.
-   **Data Preprocessing** --- handle missing values, transform
    categorical variables, scale/normalize where needed.
-   **Model Training & Evaluation** --- apply a variety of
    machine‑learning models; compare performance; choose best model(s).
-   **Pandas Profiling** --- automated data profiling report to quickly
    assess data quality and distributions.

## 📁 Repository Structure

    spaceship_titanic/
    │   .gitignore
    │   LICENSE
    │   requirements.txt
    │   README.md
    ├── data/
    ├── EDA.ipynb
    ├── Data pre-processing.ipynb
    ├── Feature engineering.ipynb
    ├── Model fitting.ipynb
    ├── Pandas Profiling EDA.ipynb

## ⚙️ Setup

    git clone https://github.com/sophieporton/spaceship_titanic.git
    cd spaceship_titanic
    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
    pip install -r requirements.txt

## 🧑‍💻 Usage

1.  Download the dataset from the Kaggle competition page.
2.  Place the files into the `data/` folder.
3.  Open the notebooks in Jupyter or VS Code.
4.  Run in order: EDA → Preprocessing → Feature Engineering → Model
    Fitting.

## 🧪 What's Inside

-   Exploratory Analysis
-   Feature Engineering (e.g., Cabin splitting)
-   Preprocessing (imputing, encoding, scaling)
-   Modelling (multiple ML algorithms)
-   Evaluation and results

## 🤝 Contribution

Contributions are welcome! Fork, branch, commit, and open a pull
request.

## 📄 License

Licensed under the Apache License 2.0.

## ✨ Acknowledgments

-   Kaggle --- Spaceship Titanic competition
-   Open‑source tools such as pandas, scikit‑learn, seaborn, etc.
