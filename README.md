# Physics-based Machine Learning to Predict Hydration Free Energies for Small Molecules

## Overview

This research project explores the application of physics-informed machine learning techniques to accurately predict hydration free energies for small molecules. The methodology combines data-driven approaches with physics-based insights to enhance predictive capabilities.

### Notebooks Included

1. **`eda_pp.ipynb`**: Conducts exploratory data analysis (EDA) and preprocessing, using visualization tools like `matplotlib` and `seaborn` to understand molecular datasets.
2. **`make_groups.ipynb`**: Organizes molecules into meaningful categories, leveraging structural or chemical properties to aid in model training.
3. **`regression.ipynb`**: Implements and evaluates regression models tailored to predict hydration free energies, using metrics like mean absolute error (MAE), mean squared error (MSE), and R-squared.

## Features

- **Physics-informed EDA**: Utilize domain knowledge for effective data preparation and analysis.
- **Data Structuring**: Tools for categorizing molecules based on features critical to hydration energy predictions.
- **Advanced Regression Models**: Machine learning models that integrate physics-based principles to improve accuracy and reliability.

## Prerequisites

Ensure the following are installed:

- Python 3.7+
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `plotly`
  - `scikit-learn`
  - `scipy`

Install dependencies via:

```bash
pip install -r requirements.txt
```

## Usage

1. **EDA and Preprocessing**:
   Open `eda_pp.ipynb` to:
   - Visualize molecular data distributions.
   - Perform feature engineering and data preprocessing.

2. **Data Grouping**:
   Use `make_groups.ipynb` for:
   - Organizing molecules based on their physical or chemical properties.
   - Structuring data to enhance model training and evaluation.

3. **Regression Modeling**:
   Run `regression.ipynb` to:
   - Train machine learning models on hydration free energy datasets.
   - Evaluate model performance using key metrics.

## Contributions

Contributions to this research are welcome. Suggestions, code improvements, and additional experiments can be submitted via pull requests.

## Authors

Marvin V Prakash, Ajeet Yadav, Dr. Pradipta Bandyopadhyay
