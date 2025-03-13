# World Happiness Report Analysis

## Project Overview
This project focuses on analyzing the World Happiness Report data across multiple years (2015-2023). The World Happiness Report is an annual publication that ranks countries based on how happy their citizens perceive themselves to be. The analysis includes data cleaning, preprocessing, exploratory data analysis, and visualization of happiness trends and factors influencing happiness across different countries and regions.

## Dataset
- **Source**: [Kaggle - World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- **Description**: The dataset contains country-level happiness scores along with economic and social factors that contribute to well-being, such as:
  - GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption

## Data Cleaning Challenges
- Merging datasets from multiple years with inconsistent column naming
- Handling missing countries across different years
- Standardizing variable names and measurement scales
- Addressing outliers and anomalies in the data
- Creating a consistent longitudinal dataset for time-series analysis

## Methodology
1. **Data Collection**
   - Gather World Happiness Report data from multiple years (2015-2023)
   - Document data sources and original column definitions

2. **Data Cleaning & Preprocessing**
   - Standardize column names across all years
   - Handle missing values and countries
   - Merge datasets into a consistent longitudinal format
   - Create additional features for analysis

3. **Exploratory Data Analysis (EDA)**
   - Analyze distributions of happiness scores and contributing factors
   - Identify correlations between happiness and various socioeconomic factors
   - Examine regional patterns and differences
   - Track changes in happiness scores over time

4. **Visualization**
   - Create interactive visualizations of global happiness patterns
   - Generate time-series plots showing happiness trends
   - Develop comparative visualizations between regions and countries
   - Build correlation heatmaps for factor analysis

5. **Insights & Conclusions**
   - Identify key factors that correlate most strongly with happiness
   - Analyze countries with significant changes in happiness
   - Examine regional patterns and disparities
   - Draw conclusions about global happiness trends

## Project Structure
```
world-happiness-analysis/
├── data/
│   ├── raw/                  # Original datasets by year
│   ├── processed/            # Cleaned and merged datasets
│   └── external/             # Any additional data sources
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_analysis.ipynb
│   └── 04_visualization.ipynb
├── src/
│   ├── data/                 # Scripts for data processing
│   ├── features/             # Scripts for feature engineering
│   └── visualization/        # Scripts for creating visualizations
├── reports/
│   ├── figures/              # Generated visualizations
│   └── final_report.md       # Summary of findings
├── requirements.txt          # Project dependencies
└── README.md                 # Project description
```

## Results & Insights
This section will be updated with key findings and visualizations after analysis is complete.

## Future Work
- Incorporate additional external datasets (e.g., COVID-19 impact, political stability)
- Develop predictive models for future happiness scores
- Create an interactive dashboard for exploring the data
- Analyze specific case studies of countries with dramatic changes

## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn

## Setup Instructions
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks in order (01 → 04)

## Contributors
- Sonu Singh

## License
This project is licensed under the MIT License - see the LICENSE file for details.