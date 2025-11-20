# Project Goal
This project serves as a foundation exercice in __regression modelling__, designed to predict the median house value based on various socio-economic and structural features of the district. The primary objective to master the end-to-end Machine Learning pipeline, from data preparation to model evaluation.

## Tech Stack & Libraries
* **Language**: Python 3.10+
* **Core Libraries**: `pandas`, `numpy` (Data Manipulation)
* **Modeling**: `scikit-learn` (Linear Regression, Ranadom Forest Regressor)
* **Visualisation**: `matplotlib`, `seaborn` (EDA)
* **Environmental Management**: `conda`, `pip`
* **Model Persistence**: `joblib`
* **Version Control**L `Git / GitHub`

## Methodology & Key Steps
The project followed a standard, repordcutible ML Workflow:
1. **Exploratory Data Analysis (EDA)**: Initial analysis revealed relationships between variables. Visualizations were used to identify feature distributions and potentials outliers.
2. **Data Processing**: Handled missing calues and scaled numerical features using **StandradScaler** to prevent dominance by features with large ranges.
3. **Modeling & Training**:
   * **Basekine Model**: **Linear Regression** was established as the initial            benchmark.
   * **Advanced Model**: A **Random Forest Regressor** was implemented to capture        complex, non-linear relationships in the data.
4. **Evaluation**: Models were strictly evaluated on a held-out test set, focusing on the **Mean Squared Error (MSE)** and **R<sup>2</sup> Score** to assess predictive accuracy and goodness of fit.
