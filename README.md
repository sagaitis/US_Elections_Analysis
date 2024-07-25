# Election Analysis Project

## Overview
This project analyzes US primary election data alongside demographic data to identify areas of strength and weakness for Democratic candidates. 
The goal is to provide insights that could help improve future election results for the Democrats.

## Summary
Although the data covers only the primaries, we uncovered potential areas of focus for future Democratic campaigns:

- **States with Small Margins**: Vermont, Maine, Connecticut, Massachusetts.
- **Challenging States**: California, New York, Illinois.
- **Regions of Strength**: East and Southeastern parts.
- **Regions of Weakness**: West, Northwest.
- **Key Battleground**: Central plains.

Demographic insights suggest:
- **Hillary Clinton**: Preferred by Hispanics, the well-educated, homeowners, and lower-income individuals.
- **Donald Trump**: Preferred by wealthier individuals and possibly those concerned about immigration.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/TuringCollegeSubmissions/psagai-DWWP.4.1.git
   cd psagai-DWWP.4.1
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
## Usage

Launch Jupyter Notebook to run the analysis:
  ```bash
  jupyter notebooks
  ```
Open and run the provided notebooks.
psagai_2016_US_Elections_Analysis.ipynb

## Requirements

pandas==2.2.2
matplotlib==3.9.0
seaborn==0.13.2
statsmodels==0.14.1
folium==0.17.0
geopandas==1.0.0
branca==0.7.0
