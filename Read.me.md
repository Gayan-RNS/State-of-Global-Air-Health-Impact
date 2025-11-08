# \# Global Air Pollution Health Burden Analysis (1990-2023)



## \## Project Overview

This repository contains the data cleaning, exploratory analysis, and comparative statistical modeling of the global health burden attributable to air pollution, using data from the State of Global Air (SOGA).



The primary goal is to quantify and visualize the trends in premature \*\*Deaths\*\* and \*\*Disability-Adjusted Life Years (DALYs)\*\* due to air pollution across over 160 countries from 1990 to 2023.



#### \## Data Source

\* \*\*Source:\*\* State of Global Air (SOGA) / Global Burden of Disease (GBD) Study

\* \*\*Link:\*\* \[https://www.stateofglobalair.org/data/](https://www.stateofglobalair.org/data/)

\* \*\*Key Measures:\*\*

&nbsp;   \* `death`: Number of premature deaths attributed to air pollution.

&nbsp;   \* `daly`: Disability-Adjusted Life Years attributed to air pollution (measure of years lost due to premature mortality and disability).

&nbsp;   \* `Pollutant Names`: Air Pollution (All sources) and PM2.5.



#### \## Key Analysis Areas \& Findings



\### 1. Descriptive and Exploratory Analysis (Completed)

\* \*\*Global Trends:\*\* Visualized the increase in global deaths attributed to air pollution and PM2.5 between 1990 and 2023.

\* \*\*Geographic Distribution:\*\* Identified \*\*China\*\* and \*\*India\*\* as the top two countries for total burden in 2023, with \*\*India\*\* leading the DALY burden and \*\*China\*\* leading the Death burden.



\### 2. Comparative Analysis (DALY-to-Death Ratio)

\* \*\*Objective:\*\* Calculate the DALY-to-Death Ratio to identify countries where air pollution is most severely impacting younger populations (i.e., causing higher Years of Life Lost).

\* \*\*Key Finding:\*\* Countries in \*\*Sub-Saharan Africa\*\* (e.g., Niger, Somalia, Mali) show the highest ratios (up to ~68 DALYs per death), indicating a critical health crisis of premature mortality and disability in these regions.



\### 3. Uncertainty Analysis (Pending)

\* \*Task:\* Calculate and visualize the 95% Uncertainty Intervals ($\\text{Burden Upper} - \\text{Burden Lower}$) for burden estimates to assess the precision of the SOGA/GBD model results over time.



\### 4. Advanced Modeling (Pending)

\* \*Task:\* Use time-series regression to model the rate of change in air pollution burden and prepare the dataset for multi-country panel data analysis.

#### 

#### \## Technology Stack

\* \*\*Language:\*\* Python

\* \*\*Libraries:\*\* Pandas, NumPy, Matplotlib

\* \*\*Environment:\*\* Jupyter Notebooks or Python scripts

#### 

#### \## Repository Contents

\* `Final data set-Global Air Pollution (2025-11-08).csv`: The final, cleaned dataset used for all analyses.

\* `analysis\_notebook.ipynb` (Suggested): The main notebook containing the complete analysis code and visualizations.

\* `plots/`: Directory containing generated PNG/SVG visualizations (e.g., `global\_death\_burden\_trend.png`).

\* `scripts/` (Optional): Contains any final Python scripts for data processing or modeling.



\## How to Use

1\.  \*\*Clone the repository:\*\*

&nbsp;   ```bash

&nbsp;   git clone \[https://github.com/YourUsername/Global-Air-Pollution-Burden-Analysis.git](https://github.com/YourUsername/Global-Air-Pollution-Burden-Analysis.git)

&nbsp;   ```

2\.  \*\*Install dependencies:\*\*

&nbsp;   ```bash

&nbsp;   pip install pandas numpy matplotlib

&nbsp;   ```

3\.  \*\*Run the analysis:\*\* Open and execute the cells in the `analysis\_notebook.ipynb` file.

