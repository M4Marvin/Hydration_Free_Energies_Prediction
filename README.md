# Physics-based Machine Learning to Predict Hydration Free Energies for Small Molecules

## Overview

This research project explores the application of physics-informed machine learning techniques to accurately predict hydration free energies for small molecules. The methodology combines data-driven approaches with physics-based insights to enhance predictive capabilities.

## Notebooks Included

1. `eda_pp.ipynb`: Conducts exploratory data analysis (EDA) and preprocessing, using visualization tools like `matplotlib` and `seaborn` to understand molecular datasets.
2. `make_groups.ipynb`: Organizes molecules into meaningful categories, leveraging structural or chemical properties to aid in model training.
3. `regression.ipynb`: Implements and evaluates regression models tailored to predict hydration free energies, using metrics like mean absolute error (MAE), mean squared error (MSE), and R-squared.

## Features

-   **Physics-informed EDA**: Utilizes domain knowledge for effective data preparation and analysis.
-   **Data Structuring**: Tools for categorizing molecules based on features critical to hydration energy predictions.
-   **Advanced Regression Models**: Machine learning models that integrate physics-based principles to improve accuracy and reliability.

## Prerequisites

Ensure the following are installed. It is highly recommended to use the provided `environment.yml` file to create a consistent environment.

-   Python 3.12.2
-   The following libraries, with the specified versions:
    -   `numpy==1.26.4`
    -   `scipy==1.15.0`
    -   `pandas==2.2.3`
    -   `scikit-learn==1.6.1`
    -   `xgboost==2.1.3`
    -   `lightgbm==4.5.0`
    -   `plotly==5.24.1`
    -   `matplotlib==3.10.0`
    -   `fastapi==0.115.7`

## Environment Setup (Recommended)

1. **Using `conda`:**

    Conda installation using miniforge -

    ```bash

    curl -L -O "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"

    bash Miniforge3-$(uname)-$(uname -m).sh
    ```

    Windows -
    [Download Miniforge3 for Windows (64-bit)](https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-Windows-x86_64.exe)

    It is highly recommended to use `conda` to create an environment with the specified dependencies. This ensures that you have the correct versions of all the required packages.

    - Create the environment from the `environment.yml` file:

        ```bash
        conda env create -f environment.yml
        ```

    - Activate the environment:

        ```bash
        conda activate scis
        ```

2. **Alternative: Using `pip` (Not Recommended):**

    While not recommended, you can attempt to install the dependencies using `pip`. However, this may lead to version conflicts or other issues.

    - Create a `requirements.txt` file with the following content:

        ```yml
        numpy==1.26.4
        scipy==1.15.0
        pandas==2.2.3
        scikit-learn==1.6.1
        xgboost==2.1.3
        lightgbm==4.5.0
        plotly==5.24.1
        matplotlib==3.10.0
        fastapi==0.115.7
        ```

    - Install the dependencies:

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

## Reference Links

Add the relevant links here, such as:

-   <https://github.com/MobleyLab/FreeSolv>
-   Link to the GitHub repository.
-   Links to any relevant datasets or external resources.
-   Links to documentation for the specific libraries used.
