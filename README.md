# Japan Life Expectancy Analysis

This project explores the relationship between life expectancy and various health and demographic indicators in Japan. The objective is to identify key factors that influence longevity using data analysis and visualization techniques.

## Objectives

- Understand the distribution and trends in life expectancy across Japan.
- Identify correlations between life expectancy and other health metrics such as physician density, health expenditure, and GDP.
- Provide actionable insights that could inform healthcare policy and resource allocation.

## Dataset

The dataset (`Japan_life_expectancy.csv`) contains numerical and categorical variables related to life expectancy, healthcare availability, and economic factors in Japan. It includes indicators such as:
- Life Expectancy
- Physician Density
- Health Expenditure
- GDP per Capita
- Additional demographic and health features

## Methods Used

- **Exploratory Data Analysis (EDA)**
  - Data profiling, summary statistics, missing value analysis
- **Correlation Analysis**
  - Pearson, Spearman, and Kendall coefficients
  - Heatmaps for visualizing correlation matrices
- **Visualization**
  - Scatter plots with regression lines
  - Heatmaps for pairwise relationships

## Key Findings

- There are moderate to strong positive correlations between life expectancy and physician density, GDP per capita, and health expenditure.
- Investment in healthcare infrastructure and access is strongly associated with higher life expectancy.
- Correlation insights can inform policies aimed at improving health outcomes and managing aging population trends.

## Tools and Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook

## Future Work

- Compare Japan’s indicators with other countries to provide global context.
- Conduct time series analysis to examine trends over the years.
- Explore causal relationships or predictive modeling using regression or ML methods.

## How to Run

1. Open the Jupyter Notebook `Japan_Life_Expectancy_Insights.ipynb`.
2. Ensure the dataset `Japan_life_expectancy.csv` is in the same directory.
3. Run the cells sequentially to reproduce the analysis and visualizations.

---

Feel free to fork, reuse, or extend this analysis for your own learning or applications.
