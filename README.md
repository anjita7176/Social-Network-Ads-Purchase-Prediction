# Social Network Ads — Purchase Prediction

A learning project that explores Logistic Regression for predicting purchase outcomes from age and salary. It demonstrates basic data inspection, visualization, a reproducible train/test split, feature scaling, and class-wise evaluation.

## Dataset

The user-provided `Social_Network_Ads.csv` is included in `data/`. It contains 400 rows with `User ID`, `Gender`, `Age`, `Salary`, and `Purchased`. The notebook uses only `Age` and `Salary`; identifiers and gender are excluded from model training.

## Run the notebook

1. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Start Jupyter from the repository root:

   ```bash
   jupyter notebook
   ```

3. Open `social_network_ads_logistic_regression.ipynb` and run all cells. The notebook loads `data/Social_Network_Ads.csv` with a repository-relative path.

The model uses a stratified 70/30 split (`random_state=42`) and a `StandardScaler` + `LogisticRegression` pipeline. Run the evaluation cells to see accuracy, precision, recall, F1-score, and a confusion matrix for that split. Results are for this small educational dataset and should not be treated as production performance.

## Tools

Python · Pandas · Matplotlib · Seaborn · scikit-learn · Jupyter Notebook

## License

No license has been selected for this repository. Confirm the dataset's redistribution terms before reusing or redistributing it.
