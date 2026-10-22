# Social Network Ads — Purchase Prediction

A beginner machine-learning notebook that explores whether a user purchases a product based on their age and salary using **Logistic Regression**.

## Project overview

The notebook uses the `Social_Network_Ads.csv` dataset and includes:
- Loading data with Pandas
- Visualising age against purchase outcome
- Splitting data into training and testing sets
- Training a Logistic Regression classifier
- Predicting purchase outcomes for sample ages
- Checking model accuracy on the test set

## Tech stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

## Project files

```text
Social-Network-Ads-Purchase-Prediction/
├── social_network_ads_logistic_regression.ipynb
├── data/
│   └── Social_Network_Ads.csv   # Add the dataset here; it was not included in the uploaded file
├── requirements.txt
├── .gitignore
└── README.md
```

## Setup

1. Clone or download this repository.
2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add `Social_Network_Ads.csv` inside the `data/` folder.
4. Open the notebook in Jupyter Notebook or Google Colab.

## Dataset note

The uploaded notebook refers to `/content/Social_Network_Ads.csv`, which is a Google Colab-style path. The CSV dataset was **not included** with the uploaded notebook. Before publishing a runnable version, add the dataset and update the notebook's data-loading cell to use a repository-relative path such as:

```python
xxy = pd.read_csv("data/Social_Network_Ads.csv")
```

Only upload a dataset if you have the right to share it.

## Important note

This repository packages the notebook that was provided. Review the notebook's model-training and evaluation cells before presenting results publicly, and verify the reported accuracy by running it with the dataset.

## License

No license has been selected. Add a license only after deciding how you want others to use, modify, and distribute this project.
