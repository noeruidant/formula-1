# Formula 1 Data Analysis

This repository contains a detailed analysis of Formula 1 performance data. The project uses Python and its data science ecosystem to explore different datasets related to Formula 1 races, drivers, constructors, and circuits. The objective of this analysis is to evaluate the performance of drivers, particularly Charles Leclerc, and simulate potential scenarios for improvement.

## Project Structure

- **Jupyter Notebook (`analysis.ipynb`)**: The main analysis is contained within this notebook. It includes data cleaning, exploratory data analysis, and various simulations aimed at predicting performance based on historical data.
  
## Datasets

The analysis uses several datasets related to Formula 1 racing, including:
- `circuits.csv`: Information about Formula 1 circuits.
- `constructor_results.csv`: Results for constructors.
- `drivers.csv`: Information about Formula 1 drivers.
- `races.csv`: Race-specific data such as dates and locations.

These datasets were fetched from publicly available sources such as the TidyTuesday Formula 1 dataset.

## Analysis

The notebook covers the following key sections:
1. **Data Loading and Cleaning**: Initial processing of datasets, removal of irrelevant columns, handling missing values, and merging data from different sources to form a comprehensive dataset.
2. **Exploratory Data Analysis (EDA)**: 
    - Summary statistics for circuits and constructor results.
    - Visualizations (e.g., distribution plots, histograms) to explore patterns and outliers.
3. **Performance Prediction**: Using simulations based on grid positions, final race positions, and other factors to estimate performance in future seasons.
4. **Scenario Simulation**: Simulations that explore how changes in driver performance (such as improving qualifying grid positions) could affect the overall championship outcomes.

### Key Findings

- Simulations indicate that Charles Leclerc needs to improve his average qualifying grid position and reduce the variability in his race results to contend for the world championship.
- A 25% improvement in qualifying and a 12.5% reduction in result variability could lead to significant increases in total points earned per season.

## Technologies Used

- **Python**: The core language for the analysis.
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For data visualization.
- **NumPy & SciPy**: For numerical computations and statistical analysis.
- **Scikit-learn**: For modeling and simulation of future performance scenarios.

## How to Run the Notebook

1. Clone the repository:
   ```git clone https://github.com/noeruidant/formula-1.git```

2. Install the necessary dependencies:
   ```pip install -r requirements.txt```

3. Open and run the Jupyter Notebook:
   ```jupyter notebook analysis.ipynb```

## Future Work
- Integrating more detailed data such as weather conditions, pit stop times, and driver behavior to refine the performance simulations.
- Expanding the analysis to include more drivers and seasons to draw broader insights into Formula 1 race outcomes.


   
