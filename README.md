# Social Network Ads — Purchase Prediction

A beginner machine-learning project that explores purchase prediction from a user’s age and estimated salary using Logistic Regression.

## Project workflow

The notebook demonstrates:

- Loading and exploring tabular data with Pandas
- Visualizing purchase outcomes with Matplotlib and Seaborn
- Splitting data into training and test sets
- Training a Logistic Regression classifier with scikit-learn
- Generating predictions and evaluating the model

## Tools

Python · Jupyter Notebook · Pandas · NumPy · Matplotlib · Seaborn · scikit-learn

## Repository contents

- `social_network_ads_logistic_regression.ipynb` — analysis and model workflow
- `requirements.txt` — Python dependencies
- `README.md` — project documentation

## Run the notebook
   
1. Clone or download this repository.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Obtain the `Social_Network_Ads.csv` dataset from a source you are permitted to use and place it in a `data/` folder at the repository root.
4. Update the notebook’s data-loading cell to use the repository-relative path:

   ```python
   import pandas as pd
   df = pd.read_csv("data/Social_Network_Ads.csv")
   ```

5. Open and run the notebook in Jupyter Notebook or Google Colab.

## Data and results status

The CSV dataset is not included in this repository, and the notebook currently refers to a Google Colab path (`/content/Social_Network_Ads.csv`). The notebook has not been run here with the dataset, so no accuracy or other performance result is claimed. Add an appropriately licensed dataset, use the relative path above, and run the full notebook before reporting model metrics.

## License

No license has been selected for this repository yet.
