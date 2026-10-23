# Clustering, Dimensionality Reduction, and Feature Transformation

Classical machine-learning experiments in clustering, dimensionality reduction, and feature transformation, with revenue prediction among the application goals.

## Navigate the project

| File or folder | Purpose |
| --- | --- |
| [ClusterDimRedFeatTransf.py](ClusterDimRedFeatTransf.py) | Experiment implementation |
| [data/](data/) | Included datasets and supporting files |

## Data

The experiments reference:

- Google Analytics customer revenue data from [Kaggle](https://www.kaggle.com/c/ga-customer-revenue-prediction/data).
- Industrial energy data included in the repository.
- Image data available through scikit-learn.

For the Google Analytics workflow, download `train.csv` from Kaggle and place it under `data/GstoreCustomer/`. Follow the dataset provider’s access requirements and terms.

## Tech stack

| Component | Technology | Role |
| --- | --- | --- |
| Language | Python | Experiment implementation |
| Machine learning | scikit-learn | Clustering, dimensionality reduction, and feature transformation |
| Data processing | pandas and NumPy | Data preparation and numerical operations |
| Development environment | Anaconda on Windows | Original Python environment |

## Original environment

- Python 3.6.2
- scikit-learn 0.19.1
- pandas 0.23.3
- NumPy 1.15.1

## Run

With the required data and dependencies available, run:

```bash
python ClusterDimRedFeatTransf.py
