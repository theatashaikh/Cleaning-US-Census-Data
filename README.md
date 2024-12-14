# Cleaning US Census Data

This project involves cleaning, exploring, and visualizing US Census data. The dataset is divided into 10 CSV files, each containing demographic, income, and population data for different states. The goal is to process the data to create meaningful visualizations and insights.

## Project Overview

The project simulates a real-world scenario where a Data Analyst at the Census Bureau is tasked with cleaning and analyzing raw census data. The previous analyst used manual methods, which were inefficient and non-scalable. This project demonstrates how to automate these tasks using Python.

## Features

- **Data Cleaning**: 
  - Consolidating data from multiple CSV files into a single DataFrame.
  - Handling missing or inconsistent data.
  - Splitting and formatting columns for easier analysis (e.g., separating gender and population data).

- **Data Analysis**:
  - Exploring demographic trends and population distribution.
  - Investigating relationships between variables such as income and gender proportion.

- **Visualizations**:
  - Creating scatterplots, histograms, and other charts to represent data insights visually.

## Tools and Libraries

- **Python**: For data manipulation and analysis.
- **Pandas**: To clean and organize data.
- **Matplotlib and Seaborn**: For creating visualizations.

## Files in the Repository

- `Cleaning US Census Data.ipynb`: The Jupyter Notebook containing the code and explanations for this project.
- `states0.csv` to `states9.csv`: Raw data files containing US Census data.

## How to Use

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Cleaning US Census Data.ipynb"
   ```
4. Follow the steps in the notebook to see how the data is processed and visualized.

## Visualizations

The project includes the following visualizations:
- Scatterplot: Shows the relationship between average income and the proportion of women in each state.
- Histogram: Displays the distribution of total population and other variables.

## Insights

The visualizations provide insights into:
- How income levels vary with the proportion of women in a state.
- Population distribution trends across the United States.

## Future Improvements

- Include additional datasets to provide more comprehensive insights.
- Use advanced visualization tools like Plotly or Tableau.
- Build interactive dashboards for real-time data exploration.

## Author

This project was developed as part of a data science certification course to practice and demonstrate data cleaning and visualization skills. If you have any questions or feedback, feel free to reach out!
