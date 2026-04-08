## Energy Insecurity Project Description
Energy insecurity is a chronic and widespread problem in the United States, and increasing energy prices are putting further pressure on households. Energy insecurity refers to the inability of households to meet basic energy needs, often leading to difficult tradeoffs such as reducing food or medicine spending or living in unsafe temperatures.This project analyzes trends in household energy insecurity in the U.S. using the EIA Residential Energy Consumption Survey. 

## Data Sources

Data for this project comes from the U.S. Energy Information Administration (EIA) Residential Energy Consumption Survey (RECS).The analysis uses published tables from the 2015, 2020, and 2024 RECS. These tables provide aggregated data on household energy insecurity indicators.

## Methods

- Cleaned and standardized RECS tables across years
- Renamed variables for clarity and consistency
- Combined datasets into a single structured dataset
- Conducted descriptive analysis of trends over time and across regions
- Created visualizations to compare energy insecurity indicators

## Key Findings 
This project analyzes trends in energy insecurity in U.S. households using EIA RECS data from 2015, 2020, and 2024. Results show that energy insecurity has significantly since 2020, with food and medical tradeoffs being the most common form. Regional differences highlight higher vulnerability in certain areas.

## Repository Structure

- `notebooks/` — analysis notebook
- `data/processed/` — cleaned dataset used for analysis
- `communication/` — figures and visual outputs

## Reproducibility

To reproduce this analysis:

1. Download RECS data tables from the EIA website (https://www.eia.gov/consumption/residential/)
2. Place files in the `data/raw/` folder
3. Run the notebook in `notebooks/` from top to bottom


## Requirements
- Python 3.8+
- Packages: pandas, matplotlib, numpy, seaborn, openpyx1

## Contact
Hilary Griggs - hilarybgriggs@gmail.com

## License
Data from EIA: https://www.eia.gov/consumption/residential/
