# Machine Learning CIE 2 – Activity 1: Dataset Preparation

## Project overview
This project performs dataset inspection, data-quality checks, exploratory data analysis (EDA), missing-value handling, duplicate checking, categorical encoding and numerical feature scaling. No prediction model is trained.

## Dataset
- **Name:** Titanic Dataset
- **Format:** CSV
- **Source:** https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv
- **Direct CSV:** https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv
- **Domain:** Transport / passenger information

The notebook downloads the dataset from the source URL when executed. The actual row and column counts are printed by the notebook.

## Files
- `ML_CIE2_Activity1_Dataset_Preparation.ipynb` – complete notebook with code, explanations and visualizations.
- `README.md` – project description and execution instructions.
- `requirements.txt` – required Python libraries.
- `titanic_prepared.csv` – generated after running all notebook cells.

## Work completed
1. Loaded and inspected the Titanic CSV dataset.
2. Displayed sample rows, data types and summary statistics.
3. Identified missing values and calculated their percentages.
4. Filled missing age values using the median and missing embarked values using the mode.
5. Checked and removed exact duplicate records, if present; standardized text formatting.
6. Performed EDA using frequency counts, a histogram, a count plot and a box plot.
7. Removed redundant, unsuitable or target-leaking columns with explanations.
8. Applied one-hot encoding to selected categorical features.
9. Standardized selected numerical input features using `StandardScaler`.
10. Verified the final dataset and saved it as `titanic_prepared.csv`.

## How to run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells from top to bottom. Internet access is required to download the source CSV.
3. The notebook creates `titanic_prepared.csv` in the current working directory.
4. Download the generated CSV and include it in the GitHub repository.

## Important note about scaling
This is a data-preparation exercise and does not train a model. In a real predictive workflow, split the dataset first and fit preprocessing transformations such as scaling on the training set only.

## Faculty profile and acknowledgement
Faculty profile: https://github.com/Princy2129

“This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources:
https://github.com/Princy2129”
