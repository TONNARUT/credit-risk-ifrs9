# credit-risk-ifrs9
Build an end-to-end credit risk model that predicts probability of default and estimates IFRS 9 expected credit loss, documented and presented to bank-management standard.
## Data

This project uses the **Home Credit Default Risk** dataset from Kaggle.

1. Download `application_train.csv` from [Kaggle](https://www.kaggle.com/c/home-credit-default-risk/data) (accept the competition rules first).
2. Place it in the `data/` folder.

Data files are not included in this repo because of size and licence (see `.gitignore`).

## Project Structure

- `data/`: raw data (not tracked)
- `notebooks/`: EDA and modelling notebooks
- `src/`: reusable Python code
- `reports/`: data log, model documentation, slides
