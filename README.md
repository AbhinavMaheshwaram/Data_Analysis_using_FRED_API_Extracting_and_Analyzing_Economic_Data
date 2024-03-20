
# Data Analysis using FRED API: Extracting and Analyzing Economic Data

## Overview

This project demonstrates the process of data analysis using the Federal Reserve Economic Data (FRED) API. The focus is on extracting and analyzing economic data, specifically unemployment and labor force participation rates in the United States. The project involves data extraction, cleaning, exploratory analysis, visualization, and interpretation of findings.

## Steps Involved

1. **Importing Libraries:**
   - Necessary libraries for data manipulation, analysis, and visualization are imported, including pandas, numpy, matplotlib.pyplot, and plotly.express.

2. **Connecting to FRED API:**
   - A connection is established to the FRED API using the provided API key. This allows retrieval of economic data series from the St. Louis Fed database.

3. **Data Extraction:**
   - Unemployment and labor force participation data are extracted from FRED using relevant series IDs. The extracted data is then explored and analyzed.

4. **Data Acquisition from FRED API:**
   - Unemployment and participation rate data are retrieved, filtered, and cleaned. Summary statistics are calculated to understand the data distributions.

5. **Pulling and Analyzing Unemployment Data:**
   - State-level unemployment data is pulled and analyzed. Data cleaning techniques are applied, and exploratory analysis is conducted to understand temporal trends.

6. **Exploring State-Level Unemployment Data:**
   - State-level unemployment data is visualized using line plots to observe trends over time. Insights are drawn from the data, including the impact of events like the COVID-19 pandemic on unemployment rates.

7. **Pulling and Analyzing Participation Data:**
   - Labor force participation rate data for states are retrieved, cleaned, and analyzed. Comparative analysis is conducted to understand variations in participation rates across states.

8. **Analyzing Unemployment vs. Participation Rates:**
   - Unemployment and participation rates are compared for multiple states. Interactive visualizations are created to explore trends and relationships between the two variables.

9. **Creating Interactive Visualizations:**
   - Interactive plots are generated using Plotly to visualize unemployment and participation rates by state. Users can interactively explore the data by selecting specific states.

10. **Conclusion:**
    - The project concludes with a summary of the analysis, highlighting key findings and insights drawn from the data. Suggestions for further exploration and analysis are provided.

## Preserving Data for Future Research

The cleaned and processed data is preserved in CSV format for future research and analysis. Two CSV files, "unemp_states.csv" and "part_states.csv," contain state-level unemployment and participation rate data, respectively.

## Resources

- **Data Acquisition:** Links to FRED API documentation and dataset catalog for accessing economic data.
- **Data Analysis with Python:** Resources for learning data analysis techniques using Pandas, Matplotlib, and Plotly.
- **General Data Analysis Resources:** Additional resources for exploratory data analysis, data cleaning, and storytelling with data visualization.
