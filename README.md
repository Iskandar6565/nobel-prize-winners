# Nobel Prize Laureates Data Analysis

## Project Overview
This project explores a dataset of Nobel Prize laureates to identify global historical trends. Using Python and Pandas, the analysis pinpoints dominant demographics, tracks geographic shifts across decades, and isolates specific era-category combinations with peak diversity metrics.

## Key Insights & Achievements
* **Demographic Dominance:** Calculated and isolated the most frequently awarded gender (`top_gender`) and birth country (`top_country`) using categorical frequency distributions.
* **Geographic Ratio Tracking:** Engineered a custom tracking metric to compute the historical proportion of US-born winners per decade. Identified the specific decade where US-born laureates reached their highest ratio relative to global winners (`max_decade_usa`).
* **Multi-Variable Proportional Analysis:** Grouped multidimensional data by both decade and prize category to track gender proportions over time. Successfully extracted the precise decade and category combination that yielded the highest proportion of female laureates (`max_female_dict`).

## Technical Skills Demonstrated
* **Data Manipulation:** Vectorized boolean logic creation (e.g., matching string patterns for native origins and gender alignment).
* **Feature Engineering:** Extracted numerical timelines by calculating integer-based historical decades dynamically from raw year values.
* **Aggregations & Grouping:** Handled multi-column groupings (`.groupby()`) combined with statistical mean calculations (`.mean()`) to compute ratios.
* **Array Extraction:** Filtered down targeted data tables using maximum threshold constraints and converted structured Pandas Series into standard Python dictionaries.

## Technologies Used
* **Python**
* **Pandas** (Data cleaning, grouping, and advanced indexing)
* **NumPy** (Mathematical floor scaling operations)
* **Jupyter Notebook**
