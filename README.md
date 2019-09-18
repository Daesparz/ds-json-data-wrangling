# Dealing with JSON files

Use of World Bank Data to analyze projects information: finding the countries with more projects and major common topics in projects, dealing with missing data. JSON file is reading as a string when we need to extract nested elements and then is managed as a table to apply pandas tools (testing data using asserts, grouping by, sorting values and filling NaN values to clean data and interpret them rightly).

## Getting Started

### Prerequisites

- This notebook loads `data/world_bank_projects_less.json` and `data/world_bank_projects.json`. All of them in Data folder.
- [Download Anaconda](https://www.anaconda.com/distribution/).
- Run Anaconda Navigator and launch a jupyter notebook and open the file `sliderule_dsi_json_exercise.ipynb`

Packages applied in this project (numpy, pandas json) do not require installation (default packages in anaconda). They only need to be imported in the notebook.
