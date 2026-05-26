# Week 3 Project

## Project Overview
This repository contains the Week 3 DecodeLabs Data Science Internship submission. The goal is to build a classification model that predicts the `target` label using customer demographic, transaction, and regional features.

## Objective
Predict customer behavior using a structured dataset and demonstrate a complete machine learning workflow:
- Data loading and inspection
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering and encoding
- Model training and evaluation

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset
- `data/raw_data.csv` – original dataset
- `data/processed_data.csv` – cleaned dataset produced by the notebook

## Project Steps
1. Load the dataset using `pd.read_csv()`
2. Inspect structure, data types, missing values, and target balance
3. Perform EDA with distribution plots, category analysis, and correlation heatmap
4. Clean missing values and prepare categorical features
5. Apply one-hot encoding and split data into training/testing sets
6. Train a Random Forest classifier
7. Evaluate with accuracy, ROC AUC, confusion matrix, and classification report

## Results
- Accuracy: **0.875**
- ROC AUC: **0.6818**
- Visual outputs saved to `outputs/graphs`
- Model evaluation details available in `notebooks/week3_project.ipynb`

## How to Run
1. Clone the repository
2. Create and activate a virtual environment
3. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Open the notebook:
```bash
jupyter notebook notebooks/week3_project.ipynb
```
5. Run the notebook from top to bottom.

## Repository Structure
- `data/` — raw and cleaned datasets
- `notebooks/` — Jupyter notebook for the project
- `outputs/graphs/` — generated figures
- `outputs/model_results/` — reserved for saved model outputs
- `requirements.txt` — dependencies
- `.gitignore` — excluded files and folders

## Notes
- The notebook saves cleaned data to `data/processed_data.csv`.
- The model training and evaluation are reproducible using the notebook.

##Author
**Name**: Abdul Raheem Tariq
**GitHub**: [abdulraheemtariq12-hash](https://github.com/abdulraheemtariq12-hash)
**Project Repository**: [DecodeLabs-DataScience-Internship-P3](https://github.com/abdulraheemtariq12-hash/DecodeLabs-DataScience-Internship-P3)

## 📄 License

This project is for educational purposes as part of a data science internship program.

---

**⭐ If you found this analysis helpful, please give it a star on GitHub!**

