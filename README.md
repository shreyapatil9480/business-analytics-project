# Business Analytics Project

This repository provides a ready‑to‑use business analytics project that demonstrates how to perform exploratory data analysis (EDA) and build a simple predictive model using a synthetic dataset. The project is designed to showcase analytical skills relevant to **business analysis**, **program management** and **data analytics** roles.

## Project Overview

1. **Synthetic Dataset** – The `synthetic_business_data.csv` file contains 500 rows of data representing monthly sales performance across different regions and product categories. Each row includes:

   * `Month` – month in the format YYYY‑MM.
   * `Region` – geographical region (`North`, `South`, `East`, `West`).
   * `ProductCategory` – category of product (`Electronics`, `Furniture`, `Clothing`, `Food`).
   * `MarketingSpend` – simulated marketing expenditure (integer).
   * `Sales` – simulated sales revenue (integer).
   * `Profit` – simulated profit after subtracting costs (integer).
   * `CustomerSatisfaction` – customer satisfaction index (0‑100 scale).

2. **Analysis Notebook** – The `analysis.ipynb` Jupyter notebook walks through the following steps:

   * Loading and inspecting the dataset.
   * Computing summary statistics.
   * Creating EDA visualizations (bar charts, scatter plots and heatmaps).
   * Building a linear regression model to predict **Sales** based on **MarketingSpend**, **Region** and **ProductCategory**.
   * Evaluating model performance using RMSE and visualising predicted vs. actual sales.

3. **Requirements** – A `requirements.txt` file lists the Python packages needed to run the notebook.

## Usage Instructions

To reproduce the analysis on your own machine:

1. **Clone or download this repository**.
2. **Install dependencies**. It’s recommended to use a virtual environment. From the repository root:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

4. Open the `analysis.ipynb` notebook and run through the cells to see the EDA and predictive modeling results.

## Why This Project

This project demonstrates the ability to:

* Generate and work with a realistic business dataset.
* Perform descriptive and visual analytics to extract insights.
* Build and evaluate a predictive model.
* Document the process clearly for reproducibility.

## Repository Structure

```
├── synthetic_business_data.csv   # Synthetic dataset used for analysis
├── analysis.ipynb               # Executable Jupyter notebook with EDA and modeling
├── requirements.txt             # Package dependencies
└── README.md                    # Project description and instructions (this file)
```

Feel free to adapt or extend this project by experimenting with different models, adding new features, or applying advanced analytics techniques.
